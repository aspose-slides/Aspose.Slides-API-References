---
title: Union()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil operasi union antara region ini dan region yang didefinisikan oleh persegi panjang yang ditentukan.
type: docs
weight: 53
url: /id/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) metode


Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil operasi union antara region ini dan region yang didefinisikan oleh persegi panjang yang ditentukan.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Sebuah persegi panjang yang menentukan region untuk menggabungkan region ini dengan |

## Region::Union(const Rectangle\&) metode


Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil union antara region ini dan region yang didefinisikan oleh persegi panjang yang ditentukan.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Sebuah persegi panjang yang menentukan region untuk menggabungkan region ini dengan |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metode


Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil union antara region ini dan region yang didefinisikan oleh jalur yang ditentukan.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Sebuah jalur yang menentukan region untuk menggabungkan region ini dengan |

## Region::Union(const SharedPtr\<Region\>\&) metode


Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil union antara region ini dan region yang ditentukan.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Sebuah region untuk menggabungkan region ini dengan |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [RectangleF](../../rectanglef/)
* Kelas [Region](../)
* Kelas [Rectangle](../../rectangle/)
* Kelas [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Perpustakaan [Aspose.Slides](../../../)