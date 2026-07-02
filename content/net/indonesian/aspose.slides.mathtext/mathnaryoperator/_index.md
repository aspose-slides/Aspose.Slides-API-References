---
title: MathNaryOperator
second_title: Aspose.Sildes untuk Referensi API .NET
description: Menentukan objek matematika N-ary seperti Summation dan Integral. Objek ini terdiri dari sebuah operator, sebuah basis atau operand, dan batas atas serta bawah opsional. Contoh operator N-ary meliputi Summation, Union, Intersection, Integral
type: docs
weight: 8850
url: /id/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator kelas

Menentukan objek matematika N-ary, seperti Penjumlahan dan Integral. Ini terdiri dari operator, basis (atau operand), dan batas atas serta bawah opsional. Contoh operator N-ary meliputi: Penjumlahan, Union, Interseksi, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Membuat instance baru dari kelas MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Membuat instance baru dari kelas MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Membuat instance baru dari kelas MathNaryOperator. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Argumen basis |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operandenya |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Sembunyikan subskrip |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Sembunyikan superskrip |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | Lokasi batas (subskrip dan superskrip) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Karakter Operator N-ary, misalnya: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Menentukan argumen subskrip yang, misalnya, pada kasus integral, menetapkan batas bawah |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Menentukan argumen superskrip yang, misalnya, pada kasus integral, menetapkan batas atas |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Membungkus elemen matematika dengan karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Menerima fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Menerima fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau karakter lain |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Menerima integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Menerima integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Menerima integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Menerima integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Menerima integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Menggabungkan teks matematika dan membentuk blok matematika |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan bar di atas elemen ini |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang diberikan. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang diberikan. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematika lainnya. Objek yang dibungkus dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam array vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan bar di bagian bawah elemen ini |

### Contoh

Contoh:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathNaryOperator](../imathnaryoperator)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->