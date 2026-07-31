---
title: Rectangle()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru dari objek Rectangle yang merepresentasikan sebuah persegi panjang dengan koordinat X dan Y serta nilai lebar dan tinggi diatur ke 0.
type: docs
weight: 1
url: /id/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() konstruktor

Membuat sebuah instance baru dari objek [Rectangle](../) yang merepresentasikan sebuah persegi panjang dengan koordinat X dan Y serta nilai lebar dan tinggi diatur ke 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) konstruktor

Membuat sebuah instance baru dari objek [Rectangle](../) yang merepresentasikan sebuah persegi panjang dengan koordinat yang ditentukan untuk sudut kiri atasnya serta lebar dan tinggi.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | Nilai koordinat X dari sudut kiri atas persegi panjang |
| y | int | Nilai koordinat Y dari sudut kiri atas persegi panjang |
| width | int | Lebar persegi panjang |
| height | int | Tinggi persegi panjang |

## Rectangle::Rectangle(const Point\&, const Size\&) konstruktor

Membuat sebuah instance baru dari objek [Rectangle](../) yang merepresentasikan sebuah persegi panjang dengan koordinat sudut kiri atasnya ditentukan sebagai sebuah instance dari kelas [Point](../../point/) dan lebar serta tingginya sebagai sebuah instance dari kelas [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Menentukan lokasi sudut kiri atas persegi panjang |
| size | const [Size](../../size/)\& | Menentukan lebar dan tinggi persegi panjang |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) konstruktor

Membuat sebuah instance baru dari objek [Rectangle](../) yang merepresentasikan persegi panjang yang setara dengan yang ditentukan.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Sebuah instance dari kelas **System::Windows::Forms::Screen::Rectangle_** yang menentukan posisi dan ukuran persegi panjang yang akan direpresentasikan oleh objek yang sedang dibangun |

## Lihat Juga

* Kelas [Rectangle](../)
* Kelas [Point](../../point/)
* Kelas [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)