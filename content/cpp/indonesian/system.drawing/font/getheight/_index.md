---
title: GetHeight()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan jarak spasi baris dari font yang direpresentasikan oleh objek saat ini, dalam satuan saat ini dari objek Graphics yang ditentukan.
type: docs
weight: 14
url: /id/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) metode

Mengembalikan jarak spasi baris dari font yang direpresentasikan oleh objek saat ini, dalam satuan saat ini dari objek [Graphics](../../graphics/) yang ditentukan.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Objek [Graphics](../../graphics/) yang menentukan satuan pengukuran |

## Font::GetHeight(float) metode

Mengembalikan tinggi font yang direpresentasikan oleh objek saat ini ketika digambar ke perangkat tampilan dengan resolusi vertikal yang ditentukan.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dpi | **float** | Resolusi vertikal perangkat tampilan |

### Nilai Kembali

Tinggi font dalam piksel

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Graphics](../../graphics/)
* Kelas [Font](../)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)