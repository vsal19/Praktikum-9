# Praktikum-9

## Pertemuan 13

#### Nama  : Muhamad Faisal Ilham

#### NIM   : 312201322

#### Kelas : TI.22.A3

## Latihan : Mengimplementasikan penggunaan eksepsi pada lab-lab sebelumnya untuk mengatasi error yang ditimbulkan.

Saya menggunakan eksepsi di bagian input data, Berikut adalah tambahan kode eksepsi. <p>

```bash
while True:
        try:
            nim = int(input("Masukan NIM\t: "))
            if nim == "":
                print("NIM tidak boleh kosong")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break
        
while True:
        try:
            nilai = int(input("Masukan Nilai\t: "))
            if nilai == "":
                print("Nilai tidak boleh kosong")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break
```

Dengan menambahkan eksepsi maka : <p>

1. Saat input data kosong maka akan meminta untuk memasukan data kembali. <p>
2. Saat input NIM dan Nilai menggunakan karakter maka program akan meminta untuk memasukan angka. <p>

### TERIMAKASIH
