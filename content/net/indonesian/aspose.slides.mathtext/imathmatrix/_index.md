---
title: IMathMatrix
second_title: Aspose.Sildes for .NET Referensi API
description: Menentukan objek Matrix yang terdiri dari elemen anak yang disusun dalam satu atau lebih baris dan kolom. Penting untuk dicatat bahwa matriks tidak memiliki delimiter bawaan. Untuk menempatkan matriks dalam tanda kurung, Anda harus menggunakan objek delimiter IMathDelimiter. Argumen null dapat digunakan untuk membuat celah dalam matriks.
type: docs
weight: 8320
url: /id/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix antarmuka

Menentukan objek Matrix, yang terdiri dari elemen anak yang disusun dalam satu atau lebih baris dan kolom. Penting untuk dicatat bahwa matriks tidak memiliki delimiter bawaan. Untuk menempatkan matriks dalam tanda kurung, Anda harus menggunakan objek delimiter (IMathDelimiter). Argumen null dapat digunakan untuk membuat celah dalam matriks.

```csharp
public interface IMathMatrix : IMathElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Mengizinkan untuk mendapatkan antarmuka dasar IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Menentukan perataan vertikal relatif terhadap teks di sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Jumlah kolom dalam matriks |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Nilai jarak horizontal antara kolom dalam matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuannya diartikan sebagai twips (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuannya diartikan sebagai jumlah kenaikan 0,5 em. Dalam kasus lain diabaikan. Default: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Jenis jarak horizontal antara kolom dalam matriks; satuan jarak horizontal dapat berupa ems atau points (disimpan sebagai twips). Default: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Menyembunyikan placeholder untuk elemen matriks kosong. Default: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elemen-elemen matriks |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Lebar kolom minimum dalam twips (1/20 poin). Jarak celah (juga disebut “Column Gap” atau “Gap Width”) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Jumlah baris dalam matriks |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Nilai jarak vertikal antara baris dalam matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diartikan sebagai twips (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diartikan sebagai setengah baris. Default: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Jenis jarak vertikal antara baris dalam matriks; satuan jarak vertikal dapat berupa lines atau points (disimpan sebagai twips). Default: SingleSpacingGap (0) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Menghapus kolom yang ditentukan |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Menghapus baris yang ditentukan |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Mendapatkan perataan horizontal dari kolom yang ditentukan |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Menyisipkan kolom baru setelah yang ditentukan. Awalnya semua elemen dalam kolom baru adalah null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Menyisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen dalam kolom baru adalah null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Menyisipkan baris baru setelah yang ditentukan. Awalnya semua elemen dalam baris baru adalah null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Menyisipkan baris baru sebelum yang ditentukan. Awalnya semua elemen dalam baris baru adalah null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Mengatur perataan horizontal dari kolom yang ditentukan |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Mengatur perataan horizontal dari kolom-kolom yang ditentukan |

### Contoh

Contoh:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Lihat Juga

* antarmuka [IMathElement](../imathelement)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->