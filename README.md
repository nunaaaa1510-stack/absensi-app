# EduAbsen — Smart Attendance Management System

EduAbsen adalah aplikasi web sistem absensi modern berbasis Laravel dan React yang dirancang untuk mempermudah pengelolaan kehadiran karyawan maupun pengguna dalam sebuah organisasi, sekolah, maupun perusahaan. Sistem ini dibuat dengan tampilan modern, responsive, dan mendukung fitur absensi berbasis lokasi (location attendance) secara realtime.

Aplikasi ini dikembangkan menggunakan Laravel 13 sebagai backend dan React + Tailwind CSS sebagai frontend untuk memberikan pengalaman penggunaan yang cepat, interaktif, dan modern.

## Fitur Utama

### Authentication System

Sistem login dan autentikasi aman menggunakan Laravel Authentication dengan fitur:

* Login
* Register
* Logout
* Session management
* Role based access

### Multi Role Access

EduAbsen memiliki dua role utama:

#### Admin

Admin memiliki akses penuh terhadap sistem, seperti:

* Melihat seluruh data absensi
* Mengelola data karyawan
* Menambahkan employee tanpa perlu register manual
* Menghapus employee
* Mengakses dashboard admin
* Mengatur sistem absensi

#### Employee

Employee memiliki akses untuk:

* Melakukan check in
* Melakukan check out
* Melihat riwayat absensi pribadi
* Mengatur preferensi akun

## Attendance Features

### Check In & Check Out

Sistem absensi realtime dengan:

* Timestamp otomatis
* Validasi user login
* Riwayat absensi tersimpan otomatis

### Location Attendance

Sistem mendukung absensi berbasis lokasi menggunakan Geolocation API browser:

* Mengambil latitude & longitude user
* Menyimpan lokasi absensi ke database
* Validasi lokasi saat check in

### Auto Checkout Scheduler

Sistem dapat melakukan auto checkout berdasarkan waktu yang telah ditentukan admin melalui pengaturan sistem.

## Dashboard System

### Modern Dashboard UI

Dashboard dibuat menggunakan React dan Tailwind CSS dengan:

* Glassmorphism design
* Responsive layout
* Dark mode & Light mode
* Animated transition
* Realtime clock & greeting system

### Attendance Statistics

Dashboard menampilkan statistik seperti:

* Total attendance
* Completed attendance
* Working attendance
* Attendance activity chart

### Attendance History

User dapat melihat:

* Riwayat check in/check out
* Data kehadiran sebelumnya
* Status absensi

## Employee Management

Admin dapat:

* Menambah employee langsung dari dashboard
* Menghapus employee
* Melihat seluruh data employee
* Mengelola role pengguna

## Theme System

EduAbsen mendukung:

* Dark Mode (Blue Navy Theme)
* Light Mode (Sky Blue Theme)
* Theme switching realtime

## Technology Stack

### Backend

* Laravel 13
* PHP 8.3
* MySQL

### Frontend

* React JS
* Tailwind CSS
* Vite

### Libraries & Packages

* Lucide React Icons
* Recharts
* Laravel Breeze
* Geolocation API

## Tujuan Pengembangan

EduAbsen dibuat untuk memberikan solusi absensi digital yang:

* Modern
* Cepat
* Responsive
* Mudah digunakan
* Memiliki tampilan profesional
* Mendukung pengelolaan employee secara efisien

Sistem ini cocok digunakan untuk:

* Sekolah
* Organisasi
* Startup
* Perusahaan kecil
* Komunitas
* Kegiatan internal
