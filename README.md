#tugas microprosessor
![image](https://github.com/user-attachments/assets/4e4d7f07-6c91-45d5-bde9-9989714915c6)
#ESP32 adalah microcontroller dengan konektivitas WiFi dan Bluetooth, sering digunakan dalam sistem IoT, automasi, dan kontrol perangkat elektronik. Sebagai control unit, ESP32 berfungsi untuk membaca input dari sensor, memproses data, dan mengontrol output ke aktuator atau perangkat lain.

1. Arsitektur Control Unit ESP32
ESP32 memiliki beberapa unit kontrol utama untuk menangani berbagai tugas:

1.1. GPIO (General Purpose Input Output)
Fungsi: Mengontrol perangkat digital seperti relay, LED, dan tombol.
Jumlah: ±39 pin GPIO (tergantung varian ESP32).
Contoh:
Menyalakan/mematikan lampu LED dengan GPIO output.
Membaca status tombol dengan GPIO input.
1.2. PWM (Pulse Width Modulation)
Fungsi: Mengontrol kecepatan motor, kecerahan LED, atau sinyal servo.
Contoh:
Mengontrol kecepatan kipas DC berdasarkan suhu.
Mengontrol sudut servo untuk sistem robotik.
1.3. ADC (Analog to Digital Converter)
Fungsi: Membaca sensor analog seperti potensiometer, LDR, atau sensor suhu analog.
Jumlah: 18 pin ADC (12-bit resolusi).
Contoh:
Membaca sensor suhu LM35 untuk monitoring ruangan.
1.4. I2C (Inter-Integrated Circuit)
Fungsi: Berkomunikasi dengan banyak sensor dan modul hanya dengan 2 kabel (SDA & SCL).
Contoh:
Membaca sensor suhu & kelembaban DHT22.
Menampilkan data di OLED Display SSD1306.
1.5. SPI (Serial Peripheral Interface)
Fungsi: Mengontrol sensor atau modul kecepatan tinggi seperti kartu SD atau layar TFT.
Contoh:
Menghubungkan modul RFID MFRC522.
Menyimpan data pada microSD.
1.6. UART (Universal Asynchronous Receiver-Transmitter)
Fungsi: Berkomunikasi dengan modul eksternal seperti GPS, Bluetooth, atau sensor serial.
Contoh:
Menghubungkan modul GPS NEO-6M untuk tracking.
Berkomunikasi dengan Arduino atau Raspberry Pi.
1.7. WiFi & Bluetooth
Fungsi: Menghubungkan ESP32 ke Internet atau perangkat lain.
Contoh:
Mengontrol lampu dari aplikasi mobile via WiFi.
Mengirim data ke cloud (MQTT, Firebase, ThingSpeak).
![image](https://github.com/user-attachments/assets/d9ca78a6-311d-4d7e-8ee5-7ad4a0f2c66e)
#Raspberry Pi adalah komputer single-board (SBC) yang berfungsi sebagai control unit dalam berbagai sistem otomasi, IoT, dan robotika. Dengan kemampuan menjalankan sistem operasi (Linux/Raspberry Pi OS), Raspberry Pi dapat mengontrol berbagai perangkat melalui GPIO, I2C, SPI, UART, serta komunikasi jaringan (WiFi, Ethernet, Bluetooth).

1. Arsitektur Control Unit Raspberry Pi
Sebagai control unit, Raspberry Pi mengelola berbagai input dan output melalui fitur berikut:

1.1. GPIO (General Purpose Input Output)
Fungsi: Mengontrol dan membaca status perangkat digital.
Jumlah: ±40 pin (tergantung model).
Contoh:
✅ Mengontrol relay untuk menyalakan/mematikan lampu.
✅ Membaca input dari tombol atau sensor gerak (PIR).
1.2. PWM (Pulse Width Modulation)
Fungsi: Mengontrol kecepatan motor atau kecerahan LED.
Contoh:
✅ Mengontrol motor kipas berdasarkan suhu ruangan.
✅ Menggerakkan servo untuk sistem robotik.
1.3. I2C (Inter-Integrated Circuit)
Fungsi: Berkomunikasi dengan sensor dan modul berbasis I2C.
Contoh:
✅ Membaca sensor suhu dan tekanan (BME280, MPU6050).
✅ Menampilkan data di OLED atau LCD I2C.
1.4. SPI (Serial Peripheral Interface)
Fungsi: Berkomunikasi dengan perangkat berkecepatan tinggi.
Contoh:
✅ Menghubungkan sensor RFID MFRC522.
✅ Membaca data dari modul SD Card.
1.5. UART (Universal Asynchronous Receiver-Transmitter)
Fungsi: Menghubungkan modul komunikasi berbasis serial.
Contoh:
✅ Menghubungkan modul GSM/GPS (SIM800L, NEO-6M).
✅ Menghubungkan Arduino untuk komunikasi antar board.
1.6. WiFi & Ethernet
Fungsi: Mengontrol dan menghubungkan Raspberry Pi ke jaringan.
Contoh:
✅ Home Automation Hub dengan Home Assistant.
✅ CCTV streaming menggunakan MotionEyeOS.
