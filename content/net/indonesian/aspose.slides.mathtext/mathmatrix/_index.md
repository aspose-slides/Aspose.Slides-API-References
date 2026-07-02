---
title: MathMatrix
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menentukan objek Matrix yang terdiri dari elemen anak yang disusun dalam satu atau lebih baris dan kolom. Penting untuk dicatat bahwa matriks tidak memiliki pembatas bawaan. Untuk menempatkan matriks dalam tanda kurung, Anda harus menggunakan objek delimiter IMathDelimiter. Argumen null dapat digunakan untuk membuat celah dalam matriks.
type: docs
weight: 8830
url: /id/aspose.slides.mathtext/mathmatrix/
---
## Kelas MathMatrix

Menentukan objek Matrix, yang terdiri dari elemen anak yang disusun dalam satu atau lebih baris dan kolom. Penting untuk dicatat bahwa matriks tidak memiliki pembatas bawaan. Untuk menempatkan matriks dalam tanda kurung, Anda harus menggunakan objek delimiter (IMathDelimiter). Argumen null dapat digunakan untuk membuat celah dalam matriks.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktor

| Name | Description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Menginisialisasi instance baru dari kelas MathMatrix. |

## Properti

| Name | Description |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Menentukan perataan vertikal relatif terhadap teks di sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Jumlah kolom dalam matriks |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Nilai jarak horizontal antara kolom dalam matriks; Jika ColumnGapRule diatur ke 3 ("Exactly"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika ColumnGapRule diatur ke 4 ("Multiple"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0,5 em. Dalam kasus lain diabaikan. Default: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Jenis jarak horizontal antara kolom dalam matriks; Satuan jarak horizontal dapat berupa ems atau points (disimpan sebagai twips). Default: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Menyembunyikan placeholder untuk elemen matriks kosong Default: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Elemen matriks |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Lebar kolom minimum dalam twip (1/20 poin) Jarak celah (juga disebut “Column Gap” atau “Gap Width”) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Jumlah baris dalam matriks |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Nilai jarak vertikal antara baris dalam matriks; Jika RowGapRule diatur ke 3 ("Exactly"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika RowGapRule diatur ke 4 ("Multiple"), maka satuan diinterpretasikan sebagai setengah baris. Default: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Jenis jarak vertikal antara baris dalam matriks; Satuan jarak vertikal dapat berupa lines atau points (disimpan sebagai twips). Default: SingleSpacingGap (0) |

## Metode

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Menghapus kolom yang ditentukan |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Menghapus baris yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Mendapatkan elemen anak |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Mendapatkan perataan horizontal dari kolom yang ditentukan |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau yang lain |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Menyisipkan kolom baru setelah yang ditentukan. Awalnya semua elemen di kolom baru adalah null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Menyisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen di kolom baru adalah null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Menyisipkan baris baru setelah yang ditentukan. Awalnya semua elemen di baris baru adalah null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Menyisipkan baris baru sebelum yang ditentukan. Awalnya semua elemen di baris baru adalah null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Mengambil integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Mengambil integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Menggabungkan teks matematika dan membentuk blok matematika |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan garis di atas elemen ini |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Mengatur perataan horizontal dari kolom yang ditentukan |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Mengatur perataan horizontal dari kolom yang ditentukan |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Mengambil batas bawah |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Mengambil batas bawah |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Membuat subskrip |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Membuat subskrip |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di sebelah kiri |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Membuat subskrip dan superskrip di sebelah kiri |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di sebelah kanan |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Membuat subskrip dan superskrip di sebelah kanan |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Membuat superskrip |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Membuat superskrip |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Mengambil batas atas |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Mengambil batas atas |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Menempatkan elemen ini dalam kotak batas |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Menempatkan elemen ini dalam kotak batas |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau contoh teks matematika lainnya. Objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik perataan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam array vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan garis di bawah elemen ini |

### Contoh

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathMatrix](../imathmatrix)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->