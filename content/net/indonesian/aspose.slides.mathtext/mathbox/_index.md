---
title: MathBox
second_title: Aspose.Sildes untuk .NET API Reference
description: Menentukan pembungkus logis (pengemasan) elemen matematis. Misalnya, sebuah objek yang dibungkus dapat berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutusan baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. Sebagai contoh, operator harus dibungkus untuk mencegah pemutusan baris.
type: docs
weight: 8610
url: /id/aspose.slides.mathtext/mathbox/
---
## Kelas MathBox

Menentukan pembungkus logis (pengemasan) dari elemen matematis. Misalnya, objek yang dibungkus dapat berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutusan baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. Sebagai contoh, operator "==" harus dibungkus untuk mencegah pemutusan baris.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Menginisialisasi MathBox dengan elemen yang ditentukan sebagai argumen |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Jika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditetapkan dalam persamaan lain dapat diselaraskan dengannya. Default: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Argumen dasar |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential Jika true, kotak berperilaku sebagai diferensial (misalnya, 𝑑𝑥 dalam integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. Default: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break menentukan apakah ada pemutusan baris pada awal objek Box, sehingga baris membungkus pada awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematis yang akan digunakan sebagai titik penyelarasan untuk baris teks matematis saat ini. Nilai yang mungkin: 1..255 Default: 0 (tidak ada pemutusan eksplisit) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break Properti ini menentukan properti "unbreakable" pada kotak objek. Jika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Jika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Default: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. Jika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemutusan baris dan dapat diselaraskan dengan operator lain. Operator Emulator sering digunakan ketika satu atau lebih glyph digabungkan menjadi sebuah operator, seperti '=='. Nilai default: false |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat sebuah pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat sebuah pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Menggunakan fungsi argumen dengan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Menggunakan fungsi argumen dengan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau yang lain |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Menggunakan integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Menggunakan integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Menggunakan integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Menggunakan integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Menggunakan integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Menggabungkan elemen matematis dan membentuk blok matematis |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Menggabungkan teks matematis dan membentuk blok matematis |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan garis di bagian atas elemen ini |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Menentukan akar matematis dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Menentukan akar matematis dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Mengambil batas bawah |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Mengambil batas bawah |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Membuat subskrip |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Membuat subskrip |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di kiri |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Membuat subskrip dan superskrip di kiri |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di kanan |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Membuat subskrip dan superskrip di kanan |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Membuat superskrip |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Membuat superskrip |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Mengambil batas atas |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Mengambil batas atas |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Menempatkan elemen ini dalam kotak-bingkai |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Menempatkan elemen ini dalam kotak-bingkai |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau contoh lain dari teks matematis. Sebuah objek yang dibungkus dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutusan baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam larik vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan garis di bagian bawah elemen ini |

### Contoh

Example:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathBox](../imathbox)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->