---
title: MathElementBase
second_title: Aspose.Sildes untuk Referensi API .NET
description: Kelas dasar untuk IMathElement dengan implementasi beberapa metode yang umum untuk semua kelas turunan. Hanya untuk penggunaan internal. Kelas turunan harus berupa IMathElement.
type: docs
weight: 8660
url: /id/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase kelas

Kelas dasar untuk IMathElement dengan implementasi beberapa metode yang umum untuk semua kelas turunan. Hanya untuk penggunaan internal. Kelas turunan harus berupa IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di bagian atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Membungkus elemen matematika dalam karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Menggunakan fungsi argumen dengan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Menggunakan fungsi argumen dengan instance ini sebagai nama fungsi |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau karakter lain |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Mengambil integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Mengambil integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Mengambil integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Menggabungkan teks matematika dan membentuk blok matematika |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan batang di bagian atas elemen ini |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Menentukan akar matematika dengan derajat tertentu dari argumen yang diberikan |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Menentukan akar matematika dengan derajat tertentu dari argumen yang diberikan |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Mengambil batas bawah |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Mengambil batas bawah |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Membuat subskrip |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Membuat subskrip |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di sebelah kiri |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Membuat subskrip dan superskrip di sebelah kiri |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di sebelah kanan |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Membuat subskrip dan superskrip di sebelah kanan |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Membuat superskrip |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Membuat superskrip |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Mengambil batas atas |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Mengambil batas atas |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Menempatkan elemen ini dalam kotak batas |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Menempatkan elemen ini dalam kotak batas |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau instance teks matematika lainnya. Objek yang dibungkus dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam susunan vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan batang di bagian bawah elemen ini |

### Lihat Juga

* antarmuka [IMathElement](../imathelement)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->