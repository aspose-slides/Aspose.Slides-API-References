---
title: MathSubscriptElement
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menentukan objek subskrip yang terdiri dari basis dan subskrip berukuran lebih kecil yang ditempatkan di bawah dan ke kanan.
type: docs
weight: 8980
url: /id/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement kelas

Menentukan objek subskrip, yang terdiri dari basis dan subskrip berukuran lebih kecil yang ditempatkan di bawah dan ke kanan.

```csharp
public sealed class MathSubscriptElement : BaseScript, IMathSubscriptElement
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathSubscriptElement](mathsubscriptelement)(IMathElement, IMathElement) | Menginisialisasi instance baru dari kelas MathSubscriptElement. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Argumen basis |
| [Subscript](../../aspose.slides.mathtext/mathsubscriptelement/subscript) { get; } | Subskrip |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Membungkus elemen matematika dengan karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Menggunakan fungsi dari sebuah argumen dengan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Menggunakan fungsi dari sebuah argumen dengan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathsubscriptelement/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau yang lain |
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
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau instance teks matematika lainnya. Objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemisah baris, atau dikelompokkan sehingga tidak memungkinkan pemisahan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam susunan vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan garis di bagian bawah elemen ini |

### Contoh

Contoh:

```csharp
[C#]
MathSubscriptElement subscriptElement = new MathematicalText("N").SetSubscript("i");
```

### Lihat Juga

* kelas [BaseScript](../basescript)
* antarmuka [IMathSubscriptElement](../imathsubscriptelement)
* ruangnama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->