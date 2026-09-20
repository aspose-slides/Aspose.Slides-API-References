---
title: MathArray class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/matharray/
---
## MathArray kelas

Menentukan array vertikal dari persamaan atau objek matematika apa pun

**Inheritance:**[`MathArray`](/slides/python-net/id/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathArray menampilkan anggota berikut:

## Konstruktor

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/id/aspose.slides.mathtext/matharray/__init__/#imathelement) | Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya |
| [`__init__(self, elements)`](/slides/python-net/id/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Properti

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/id/aspose.slides.mathtext/matharray/arguments/) | Kumpulan item dalam array |
| [`base_justification`](/slides/python-net/id/aspose.slides.mathtext/matharray/base_justification/) | Menentukan perataan array relatif terhadap teks di sekitarnya<br/>            Teks di luar array dapat diperalatkan dengan bagian bawah, atas, atau tengah objek array.<br/>            Nilai default: Center |
| [`maximum_distribution`](/slides/python-net/id/aspose.slides.mathtext/matharray/maximum_distribution/) | Distribusi Maksimum<br/>            Jika true, array akan diatur dengan lebar maksimum dari elemen yang menyertainya (halaman, kolom, sel, dll.). |
| [`object_distribution`](/slides/python-net/id/aspose.slides.mathtext/matharray/object_distribution/) | Distribusi Objek<br/>            Jika true, isi array diatur dengan lebar maksimum dari objek array. |
| [`row_spacing_rule`](/slides/python-net/id/aspose.slides.mathtext/matharray/row_spacing_rule/) | Tipe spasi vertikal antara elemen array<br/>            Default: SingleLineGap |
| [`row_spacing`](/slides/python-net/id/aspose.slides.mathtext/matharray/row_spacing/) | Spasi antara baris-baris array<br/>            Hanya digunakan ketika RowSpacingRule diatur ke 3 Exactly, dalam hal ini satuan ukurannya adalah poin <br/>            atau Multiple, dalam hal ini satuan ukurannya adalah setengah baris.<br/>            Default: 0 |

## Metode

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/matharray/join/#imathelement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/matharray/join/#str) | Menggabungkan teks matematika dan membentuk blok matematika |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/matharray/divide/#imathelement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/matharray/divide/#str) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/enclose/#) | Membungkus elemen matematika dalam tanda kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/matharray/enclose/#char-char) | Membungkus elemen matematika dalam karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/matharray/function/#imathelement) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/matharray/function/#str) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di sebelah kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/matharray/radical/#imathelement) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/matharray/radical/#str) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Mengambil batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Mengambil batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Mengambil batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Mengambil batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Mengambil integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Mengambil integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Mengambil integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau lainnya |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/to_border_box/#) | Menempatkan elemen ini dalam kotak batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/to_math_array/#) | Menempatkan dalam array vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/matharray/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/overbar/#) | Menetapkan bar di bagian atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/underbar/#) | Menetapkan bar di bagian bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen persamaan atau contoh teks matematika lainnya.<br/>            Sebuah objek yang dibungkus dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik perataan, <br/>            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/matharray/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathArray`](/slides/python-net/id/aspose.slides.mathtext/matharray)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)