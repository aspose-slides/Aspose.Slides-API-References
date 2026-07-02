---
title: MathBorderBox
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menggambar batas persegi panjang atau batas lain di sekitar IMathElement.
type: docs
weight: 8590
url: /id/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox kelas

Menggambar batas persegi panjang atau batas lain di sekitar IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Membuat elemen MathBorderBox dengan batas persegi panjang |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | Membuat elemen MathBorderBox |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Argumen dasar |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Sembunyikan Tepi Bawah (default adalah false) - menentukan keadaan tersembunyi atau terlihatnya tepi bawah kotak batas. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Sembunyikan Tepi Kiri (default adalah false) - menentukan keadaan tersembunyi atau terlihatnya tepi kiri kotak batas. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Sembunyikan Tepi Kanan (default adalah false) - menentukan keadaan tersembunyi atau terlihatnya tepi kanan kotak batas. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Sembunyikan Tepi Atas (default adalah false) - menentukan keadaan tersembunyi atau terlihatnya tepi atas kotak batas. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Garis coret diagonal dari Kiri Bawah ke Kanan Atas (default adalah false). Menentukan keadaan tersembunyi atau terlihatnya garis coret diagonal dari sudut kiri bawah ke sudut kanan atas kotak batas. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Garis coret Horizontal (default adalah false) - menentukan keadaan tersembunyi atau terlihatnya garis coret horizontal. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Garis coret diagonal dari Kiri Atas ke Kanan Bawah (default adalah false). Menentukan keadaan tersembunyi atau terlihatnya garis coret diagonal dari sudut kiri atas ke sudut kanan bawah kotak batas. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Garis coret Vertikal (default adalah false) - menentukan keadaan tersembunyi atau terlihatnya garis coret vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Mengambil fungsi yang ditentukan menggunakan instansi ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Mengambil fungsi yang ditentukan menggunakan instansi ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Mengambil fungsi yang ditentukan menggunakan instansi ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Mengambil fungsi yang ditentukan menggunakan instansi ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Mengambil fungsi yang ditentukan menggunakan instansi ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat fraksi dari tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat fraksi dari tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Mengambil fungsi satu argumen menggunakan instansi ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Mengambil fungsi satu argumen menggunakan instansi ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompok seperti kurung kurawal bawah atau karakter lain |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (kelompok logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematika lainnya. Objek berbentuk kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik perataan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam susunan vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan garis di bagian bawah elemen ini |

### Contoh

Contoh:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathBorderBox](../imathborderbox)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->