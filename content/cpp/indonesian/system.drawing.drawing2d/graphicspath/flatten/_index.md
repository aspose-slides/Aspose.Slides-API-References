---
title: Flatten()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghaluskan setiap kurva dalam jalur dengan mengubahnya menjadi serangkaian garis yang terhubung. Nilai flatness sebesar 0.25 digunakan.
type: docs
weight: 391
url: /id/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() metode

Menghaluskan setiap kurva dalam jalur dengan mengubahnya menjadi serangkaian garis yang terhubung. Nilai flatness sebesar 0.25 digunakan.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) metode

Menghaluskan setiap kurva dalam jalur dengan mengubahnya menjadi serangkaian garis yang terhubung. Nilai flatness sebesar 0.25 digunakan.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Matriks transformasi yang diterapkan pada jalur sebelum menghaluskan |

## GraphicsPath::Flatten(const MatrixPtr\&, float) metode

Menghaluskan setiap kurva dalam jalur dengan mengubahnya menjadi serangkaian garis yang terhubung.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Matriks transformasi yang diterapkan pada jalur sebelum menghaluskan |
| flatness | **float** | Menentukan kesalahan maksimum yang diizinkan antara kurva dan pendekatan yang di-flatten |

## Lihat Juga

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)