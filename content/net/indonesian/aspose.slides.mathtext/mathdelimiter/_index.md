---
title: MathDelimiter
second_title: Aspose.Sildes untuk Referensi API .NET
description: Menentukan objek delimiter yang terdiri dari karakter pembuka dan penutup seperti tanda kurung, kurung kurawal, kurung siku, dan batang vertikal serta satu atau lebih elemen matematika di dalamnya yang dipisahkan oleh karakter tertentu. Contoh 2 2x7C2
type: docs
weight: 8630
url: /id/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter kelas

Menentukan objek delimiter, yang terdiri dari karakter pembuka dan penutup (seperti tanda kurung, kurung kurawal, kurung siku, dan batang vertikal), serta satu atau lebih elemen matematika di dalamnya, dipisahkan oleh karakter yang ditentukan. Contoh: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Menginisialisasi MathDelimiter dengan elemen yang ditentukan sebagai argumen dasar tunggal |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Satu atau lebih elemen matematika yang dipisahkan oleh karakter delimiter |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Karakter Awalan Delimiter menentukan karakter delimiter awal, atau pembuka. Delimiter matematika adalah karakter yang mengelilingi seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Menentukan bentuk delimiter dalam objek delimiter. Ketika MathDelimiterShape.Centered, delimiter berada di tengah sumbu matematika teks matematika dan masih dapat disesuaikan untuk menyesuaikan tinggi keseluruhan kontennya. Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat sesuai dengan kontennya. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Karakter Akhir Delimiter menentukan karakter delimiter akhir, atau penutup. Delimiter matematika adalah karakter yang mengelilingi seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai default adalah true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Karakter Pemisah Delimiter menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai default: '&#x7C;'. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Menerapkan fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Menerapkan fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Menerapkan fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Menerapkan fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Menerapkan fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Membatasi argumen menggunakan karakter delimiter yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Membungkus elemen matematika dengan karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Menerapkan fungsi argumen menggunakan instance ini sebagai nama fungsi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Menerapkan fungsi argumen menggunakan instance ini sebagai nama fungsi |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Mendapatkan elemen anak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau lainnya |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Menerapkan integral tanpa batas |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Menerapkan integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Menerapkan integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Menerapkan integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Menerapkan integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Menggabungkan teks matematika dan membentuk blok matematika |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan bar di atas elemen ini |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Menerapkan batas bawah |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Menerapkan batas bawah |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Membuat subskrip |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Membuat subskrip |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di sebelah kiri |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Membuat subskrip dan superskrip di sebelah kiri |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di sebelah kanan |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Membuat subskrip dan superskrip di sebelah kanan |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Membuat superskrip |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Membuat superskrip |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Menerapkan batas atas |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Menerapkan batas atas |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Menempatkan elemen ini dalam kotak berbingkai |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Menempatkan elemen ini dalam kotak berbingkai |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematika lainnya. Objek yang dibungkus dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik aligment, berfungsi sebagai titik putus baris, atau dikelompokkan sehingga tidak memungkinkan putus baris di dalamnya |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Menempatkan dalam array vertikal |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan bar di bagian bawah elemen ini |

### Contoh

Contoh:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathDelimiter](../imathdelimiter)
* ruang nama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->