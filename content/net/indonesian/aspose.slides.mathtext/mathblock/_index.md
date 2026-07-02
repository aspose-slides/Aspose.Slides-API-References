---
title: MathBlock
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menentukan sebuah instance teks matematika yang berada dalam MathParagraph dan dimulai pada barisnya sendiri. Semua zona matematika termasuk persamaan, ekspresi, array persamaan atau ekspresi, dan formula direpresentasikan oleh blok matematika.
type: docs
weight: 8570
url: /id/aspose.slides.mathtext/mathblock/
---
## Kelas MathBlock

Menentukan sebuah instance teks matematis yang berada dalam MathParagraph dan dimulai pada barisnya sendiri. Semua zona matematika, termasuk persamaan, ekspresi, array persamaan atau ekspresi, dan formula direpresentasikan oleh blok matematika.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Menginisialisasi instance baru dari kelas MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Membuat blok matematika baru dan menempatkan elemen yang ditentukan di dalamnya. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Membuat blok matematika baru dan menempatkan elemen yang ditentukan di dalamnya. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Mendapatkan jumlah elemen matematika anak yang sebenarnya terdapat dalam koleksi. Baca-saja Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Mengembalikan false karena koleksi elemen anak dapat dimodifikasi. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Mendapatkan atau menetapkan IMathElement pada indeks yang ditentukan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Menetapkan tanda aksen (karakter di atas elemen ini). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Menambahkan elemen matematika ke akhir koleksi. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Menggunakan fungsi tertentu dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Menghapus semua elemen dari koleksi. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Menentukan apakah koleksi berisi nilai tertentu. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Menyalin ke array yang ditentukan. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Membatasi elemen anak dengan karakter pemisah (tanpa kurung). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Membungkus elemen matematika dalam tanda kurung. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Membungkus elemen anak blok ini dengan karakter tertentu seperti kurung atau karakter lain sebagai bingkai. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Membungkus elemen anak blok ini dengan karakter tertentu seperti kurung atau lain sebagai bingkai dan memisahkan dengan karakter pemisah. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Menggunakan fungsi argumen dengan instance ini sebagai nama fungsi. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Menggunakan fungsi argumen dengan instance ini sebagai nama fungsi. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Mendapatkan elemen anak. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompok seperti kurung kurawal bawah atau lainnya. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Menentukan indeks elemen matematika tertentu dalam koleksi. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Menyisipkan MathElement ke dalam koleksi pada indeks yang ditentukan. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Menggunakan integral tanpa batas. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Menggunakan integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Menggunakan integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Menggunakan integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Menggunakan integral. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Menggabungkan elemen matematika dengan blok matematika ini. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Menggabungkan teks matematika dengan blok matematika ini. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Menggabungkan blok matematika lain dengan blok ini. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Membuat operator N-ary. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Membuat operator N-ary. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Menetapkan garis di atas elemen ini. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Menghapus kemunculan pertama objek tertentu dari koleksi. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Mengambil batas bawah. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Mengambil batas bawah. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Membuat subskrip. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Membuat subskrip. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di kiri. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Membuat subskrip dan superskrip di kiri. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Membuat subskrip dan superskrip di kanan. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Membuat subskrip dan superskrip di kanan. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Membuat superskrip. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Membuat superskrip. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Mengambil batas atas. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Mengambil batas atas. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Menempatkan elemen ini dalam kotak batas. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Menempatkan elemen ini dalam kotak batas. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau instansi teks matematika lainnya. Objek yang dikotakkan dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Menempatkan elemen anak dalam susunan vertikal. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Menetapkan garis di bawah elemen ini. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Menyimpan konten [`MathBlock`](../mathblock) ini sebagai MathML. |

### Contoh

Contoh:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Lihat Juga

* kelas [MathElementBase](../mathelementbase)
* antarmuka [IMathBlock](../imathblock)
* ruangnama [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->