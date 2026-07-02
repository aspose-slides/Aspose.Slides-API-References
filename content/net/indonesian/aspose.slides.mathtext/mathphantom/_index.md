---
title: MathPhantom
second_title: Aspose.Slides untuk Referensi API .NET
description: Mewakili objek matematika phantom ltmphantgt yang memengaruhi tata letak elemen anaknya tanpa harus menampilkannya. Sebuah phantom dapat menyembunyikan ekspresi dasar sambil mempertahankan lebar, tinggi, atau kedalaman untuk menyelaraskan rumus atau memesan ruang. Visibilitas dan perilaku geometri dikendalikan oleh properti seperti Show, ZeroWid, ZeroAsc, ZeroDesc, dan Transp.
type: docs
weight: 8900
url: /id/aspose.slides.mathtext/mathphantom/
---
## MathPhantom kelas

Mewakili objek matematika phantom (<m:phant>) yang memengaruhi tata letak elemen anaknya tanpa harus menampilkannya. Sebuah phantom dapat menyembunyikan ekspresi dasar sambil mempertahankan lebar, tinggi, atau kedalaman untuk menyelaraskan rumus atau memesan ruang. Visibilitas dan perilaku geometri dikendalikan oleh properti seperti Show, ZeroWid, ZeroAsc, ZeroDesc, dan Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Menginisialisasi sebuah instance baru dari kelas [`MathPhantom`](../mathphantom) menggunakan elemen matematika dasar yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Argumen dasar |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah elemen dasar ditampilkan. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah phantom transparan untuk aturan spasi berbasis kelas. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah naik (tinggi di atas garis dasar) dari elemen dasar harus diperlakukan sebagai nol. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah turun (kedalaman di bawah garis dasar) dari elemen dasar harus diperlakukan sebagai nol. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah lebar elemen dasar harus diperlakukan sebagai nol. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bagian bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau lainnya |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Mengambil integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Mengambil integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Menggabungkan teks matematika dan membentuk blok matematika |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan bar di bagian atas elemen ini |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau contoh teks matematika lainnya. Sebuah objek berkotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam susunan vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan bar di bagian bawah elemen ini |

### Contoh

Contoh:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Sembunyikan konten
phantom.ZeroWidth = false;     // Pertahankan lebar
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathPhantom](../imathphantom)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->