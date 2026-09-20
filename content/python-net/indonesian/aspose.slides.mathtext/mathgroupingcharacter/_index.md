---
title: MathGroupingCharacter class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter kelas

Menentukan simbol pengelompokan di atas atau di bawah sebuah ekspresi, biasanya untuk menyoroti hubungan antar elemen

**Pewarisan:**[`MathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathGroupingCharacter mengekspos anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Menginisialisasi contoh baru dari kelas MathGroupingCharacter <br/>            dengan karakter pengelompokan default U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Menginisialisasi contoh baru dari kelas MathGroupingCharacter. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`base`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/base/) | Argumen dasar |
| [`character`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/character/) | Karakter Pengelompokan<br/>            Nilai default: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/position/) | Posisi karakter pengelompokan.<br/>            Default: Bawah |
| [`vertical_justification`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Justifikasi vertikal karakter grup.<br/>            Menentukan penjajaran objek relatif terhadap garis dasar.<br/>            Misalnya, ketika karakter grup berada di atas objek, <br/>            VerticalJustification of Top menandakan bahwa bagian atas objek berada pada garis dasar;<br/>            ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar<br/>            Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Menggabungkan elemen matematis dan membentuk blok matematis |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Menggabungkan teks matematis dan membentuk blok matematis |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Membuat fraksi tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Membuat fraksi tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Membungkus elemen matematika dalam tanda kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Membungkus elemen matematika dengan karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Menerima fungsi dari sebuah argumen menggunakan instansi ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Menerima fungsi dari sebuah argumen menggunakan instansi ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Menerima fungsi yang ditentukan menggunakan instansi ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Menerima fungsi yang ditentukan menggunakan instansi ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Menerima fungsi yang ditentukan menggunakan instansi ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Menerima fungsi yang ditentukan menggunakan instansi ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Menerima fungsi yang ditentukan menggunakan instansi ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di sebelah kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Menerima batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Menerima batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Menerima batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Menerima batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Menerima integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Menerima integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Menerima integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Menerima integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Menerima integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau lainnya |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Menempatkan elemen ini dalam kotak batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Menempatkan dalam susunan vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Menetapkan tanda aksen (karakter di bagian atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Menetapkan bar di atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Menetapkan bar di bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen persamaan atau contoh teks matematis lainnya.<br/>            Objek berkotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penjajaran, <br/>            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* kelas [`MathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/mathgroupingcharacter)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* pustaka [`Aspose.Slides`](/slides/python-net)