---
title: IMathElement
second_title: Aspose.Sildes untuk .NET Referensi API
description: Antarmuka dasar dari setiap elemen matematika seperti pecahan, teks matematika, fungsi, ekspresi dengan banyak elemen, dll
type: docs
weight: 8230
url: /id/aspose.slides.mathtext/imathelement/
---
## Antarmuka IMathElement

Antarmuka dasar dari setiap elemen matematika: pecahan, teks matematika, fungsi, ekspresi dengan beberapa elemen, dll

```csharp
public interface IMathElement
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Menetapkan tanda aksen (karakter di bagian atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Membuat pecahan jenis tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Membuat pecahan jenis tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Membungkus elemen matematika dalam tanda kurung |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Membungkus elemen ini dalam karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Mengambil fungsi suatu argumen menggunakan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Mengambil fungsi suatu argumen menggunakan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau karakter lain |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Mengambil integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Mengambil integral |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Menggabungkan teks matematika dan membentuk blok matematika |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Menetapkan batang di bagian atas elemen ini |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Mengambil batas bawah |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Mengambil batas bawah |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Membuat subskrip |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Membuat subskrip |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di kiri |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Membuat subskrip dan superskrip di kiri |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di kanan |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Membuat subskrip dan superskrip di kanan |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Membuat superskrip |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Membuat superskrip |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Mengambil batas atas |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Mengambil batas atas |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Menempatkan elemen ini dalam kotak bingkai |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Menempatkan elemen ini dalam kotak bingkai |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematika lainnya. Objek berkotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik kesejajaran, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Menempatkan dalam susunan vertikal |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Menetapkan batang di bagian bawah elemen ini |

### Contoh

Contoh:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Lihat Juga

* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->