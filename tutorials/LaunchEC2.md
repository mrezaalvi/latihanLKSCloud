

1. Akses link berikut: https://console.aws.amazon.com/ec2/home
![EC2 First Page](images/create-ec2-instance.png "Shiprock, New Mexico by Beau Rogers")

2. Klik tombol `Launch instance`

3. Masukkan nama dari `Instance`
![Instance Name](images/ec2-launch-instance-name-and-tags.png)

4. Pilih OS yang digunakan pada `Instance`
![Instance Application and OS Images](images/ec2-launch-instance-application-and-os-image.png)

5. Pilih `Instance type` yang memiliki **Free tier eligible**
![Instance Type](images/ec2-launch-instance-instance-type.png)

6. Pilih atau buat `Key pair` untuk nantinya digunakan untuk terhubung ke `Instance` melalui **SSH**
![Instance Key pair](images/ec2-launch-instance-key-pair.png)

7. Buat `Key pair` dengan mengisi nama **Key pair** (`Key pair name`), tipe **Key pair** (`Key pair type`) pilih RSA, format file (`Private key file format`) pilih `.pem` dan terakhir klik tombol `Create key pair`. Simpan file `Key pair` ke lokasi tertentu (`simpan pada C:\Users\[user_pada_komputer]`)
![Instance Create Key pair](images/ec2-launch-instance-key-pair-create.png)

8. Kita juga dapat memilih `Key pair` jika sudah memiliki **Key pair** sebelumnya
![Instance Choice Key pair](images/ec2-launch-instance-key-pair-choice.png)

9.  Buat `Network settings` pada `Firewall (security group)` pilih `Allow SSH traffic from`, `Allow HTTPS traffic from the internet`, dan `Allow HTTP traffic from the internet`.
![Instance Network settings](images/ec2-launch-instance-network-settings.png)

10. Klik tombol `Launch instance` untuk membuat `Instance`.
![Instance Create instance](images/ec2-launch-instance-create-instance.png)
![Instance Create instance process](images/ec2-launch-instance-create-instance-process.png)