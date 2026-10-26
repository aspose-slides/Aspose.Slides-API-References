---
title: Subtract()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengurangi nilai lebar dan tinggi dari objek SizeF yang ditentukan dari nilai koordinat X dan Y objek PointF yang bersangkutan.
type: docs
weight: 157
url: /id/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) metode


Subtracts the width and height values of the specified [SizeF](../../sizef/) object from the X and Y coordinates values of the specified [PointF](../) object correspondingly.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Titik yang akan diterjemahkan |
| size | const [SizeF](../../sizef/)\& | Objek [SizeF](../../sizef/) yang menentukan nilai-nilai yang akan dikurangkan dari nilai koordinat **point** |

### Nilai Kembali

Objek [PointF](../) baru yang nilai koordinat X-nya sama dengan hasil pengurangan nilai lebar **size** dari nilai koordinat X **point** dan nilai koordinat Y-nya sama dengan hasil pengurangan nilai tinggi **size** dari nilai koordinat Y **point**

## PointF::Subtract(const PointF\&, const Size\&) metode


Subtracts the width and height values of the specified [Size](../../size/) object from the X and Y coordinates values of the specified [PointF](../) object correspondingly.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Titik yang akan diterjemahkan |
| size | const [Size](../../size/)\& | Objek [Size](../../size/) yang menentukan nilai-nilai yang akan dikurangkan dari nilai koordinat **point** |

### Nilai Kembali

Objek [PointF](../) baru yang nilai koordinat X-nya sama dengan hasil pengurangan nilai lebar **size** dari nilai koordinat X **point** dan nilai koordinat Y-nya sama dengan hasil pengurangan nilai tinggi **size** dari nilai koordinat Y **point**

## Lihat Juga

* Kelas [PointF](../)
* Kelas [SizeF](../../sizef/)
* Kelas [Size](../../size/)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)