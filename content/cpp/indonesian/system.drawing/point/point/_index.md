---
title: Point()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek Point baru dan menginisialisasi nilai koordinat X dan Y-nya dengan 0.
type: docs
weight: 1
url: /id/system.drawing/point/point/
---
## Point::Point() konstruktor

Membuat objek [Point](../) baru dan menginisialisasi nilai koordinat X dan Y-nya dengan 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) konstruktor

Membuat objek [Point](../) baru dan menginisialisasinya dengan nilai-nilai yang ditentukan.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Nilai koordinat X |
| y | int | Nilai koordinat Y |

## Point::Point(const Size\&) konstruktor

Membuat objek [Point](../) baru dan menginisialisasi nilai koordinat X dan Y-nya dengan nilai lebar dan tinggi dari objek [SizeF](../../sizef/) yang bersangkutan.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Objek [SizeF](../../sizef/) yang nilai lebar dan tingginya digunakan untuk menginisialisasi nilai koordinat X dan Y dari objek [Point](../) yang sedang dibuat |

## Point::Point(int) konstruktor

Membuat objek [Point](../) baru dan menginisialisasi nilai koordinat X-nya dengan nilai yang terbentuk dari 16 bit tinggi integer 32-bit yang ditentukan, serta nilai koordinat Y-nya dengan nilai yang terbentuk dari 16 bit rendah integer 32-bit yang sama.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dw | int | Nilai integer 32-bit yang 16 bit tingginya menentukan nilai koordinat X dan 16 bit rendahnya menentukan nilai koordinat Y dari objek yang sedang dibuat |

## Lihat Juga

* Kelas [Point](../)
* Kelas [Size](../../size/)
* Ruang nama [System::Drawing](../../)
* Perpustakaan [Aspose.Slides](../../../)