---
title: MathAccent class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathaccent/
---
## MathAccent kelas

Menentukan fungsi aksen, terdiri dari basis dan tanda diakritik penggabungan Contoh: 𝑎́

**Pewarisan:**[`MathAccent`](/slides/python-net/id/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathAccent menampilkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | Membuat aksen matematika yang diterapkan pada elemen matematika yang ditentukan dengan nilai karakter aksen default |
| [`__init__(self, element, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | Membuat aksen matematika yang diterapkan pada elemen matematika yang ditentukan |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`base`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/base/) | Argumen ke mana aksen diterapkan |
| [`character`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/character/) | Karakter Aksen<br/>            Nilai harus berada dalam rentang (U+0300–U+036F) atau (U+20D0–U+20EF)<br/>            Nilai default: Kombinasi Aksen Sirkumfleks (U+0302) |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/join/#imathelement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/join/#str) | Menggabungkan teks matematika dan membentuk blok matematika |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/divide/#imathelement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/divide/#str) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/enclose/#) | Membungkus elemen matematika dalam tanda kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/enclose/#char-char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/function/#imathelement) | Menerima fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/function/#str) | Menerima fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Menerima fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di sebelah kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/radical/#imathelement) | Menentukan akar matematika dengan derajat tertentu dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/radical/#str) | Menentukan akar matematika dengan derajat tertentu dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | Menerima batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | Menerima batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | Menerima batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | Menerima batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Menerima integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | Menerima integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | Menerima integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | Menerima integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | Menerima integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau lainnya |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/to_border_box/#) | Menempatkan elemen ini dalam kotak batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/to_math_array/#) | Menempatkan dalam larik vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/overbar/#) | Menetapkan garis di atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/underbar/#) | Menetapkan garis di bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen persamaan atau contoh lain dari teks matematika.<br/>            Objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penjajaran, <br/>            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya. |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathaccent/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathAccent`](/slides/python-net/id/aspose.slides.mathtext/mathaccent)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)