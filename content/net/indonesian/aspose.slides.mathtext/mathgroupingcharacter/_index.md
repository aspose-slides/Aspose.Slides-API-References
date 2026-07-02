---
title: MathGroupingCharacter
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menentukan simbol pengelompokan di atas atau di bawah suatu ekspresi, biasanya untuk menyoroti hubungan antara elemen
type: docs
weight: 8740
url: /id/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter kelas

Menentukan simbol pengelompokkan di atas atau di bawah suatu ekspresi, biasanya untuk menyoroti hubungan antara elemen

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | Menginisialisasi sebuah instance baru dari kelas MathGroupingCharacter dengan karakter pengelompokan default U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | Menginisialisasi sebuah instance baru dari kelas MathGroupingCharacter. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | Argumen dasar |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | Karakter Pengelompokan Nilai default: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | Posisi karakter pengelompokan. Default: Bottom |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | Justifikasi vertikal karakter grup. Menentukan perataan objek terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification dengan nilai Top menunjukkan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar. Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di bagian atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat sebuah pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat sebuah pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung keriting bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung keriting bawah atau yang lain |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Mengambil integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Mengambil integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan bar pada bagian atas elemen ini |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau contoh teks matematis lainnya. Sebuah objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penjajaran, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam susunan vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan bar pada bagian bawah elemen ini |

### Contoh

Contoh:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathGroupingCharacter](../imathgroupingcharacter)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->