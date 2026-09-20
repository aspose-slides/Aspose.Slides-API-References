---
title: MathDelimiter class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathdelimiter/
---
## Kelas MathDelimiter

Menentukan objek pembatas, yang terdiri dari karakter pembuka dan penutup (seperti tanda kurung, kurung kurawal, kurung siku, dan bar vertikal), serta satu atau lebih elemen matematika di dalamnya, dipisahkan oleh karakter yang ditentukan. Contoh: (𝑥2); [𝑥2|𝑦2]

**Pewarisan:**[`MathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathDelimiter mengekspos anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Menginisialisasi MathDelimiter dengan elemen yang ditentukan sebagai argumen dasar tunggal |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`arguments`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/arguments/) | Satu atau lebih elemen matematika yang dipisahkan oleh karakter pembatas |
| [`beginning_character`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Karakter Awal Pembatas menentukan karakter pembatas awal, atau pembuka. <br/>            Pembatas matematika adalah karakter penutup seperti tanda kurung, kurung siku, dan kurung kurawal.<br/>            Default: '('. |
| [`separator_character`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/separator_character/) | Karakter Pemisah Pembatas menentukan karakter yang memisahkan argumen dalam objek pembatas. <br/>            Default: '\|'. |
| [`ending_character`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/ending_character/) | Karakter Akhir Pembatas menentukan karakter pembatas akhir, atau penutup. <br/>            Pembatas matematika adalah karakter penutup seperti tanda kurung, kurung siku, dan kurung kurawal.<br/>            Default: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operannya.<br/>            Nilai default adalah true. |
| [`delimiter_shape`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Menentukan bentuk pembatas dalam objek pembatas. <br/>            Ketika MathDelimiterShape.Centered, pembatas diposisikan di tengah sumbu matematika dari teks matematika <br/>            dan tetap disesuaikan agar menutupi seluruh tinggi kontennya.<br/>            Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah agar tepat sesuai dengan kontennya. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/join/#str) | Menggabungkan teks matematika dan membentuk blok matematika |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Membuat fraksi dengan bilangan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#str) | Membuat fraksi dengan bilangan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Mengepung elemen matematika dengan karakter yang ditentukan seperti tanda kurung atau karakter lainnya sebagai bingkai |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/enclose/#) | Mengepung elemen matematika dalam tanda kurung |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/function/#str) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/radical/#str) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Mengambil batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Mengambil batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Mengambil batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Mengambil batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Mengambil integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Mengambil integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Mengambil integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau lainnya |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Menempatkan elemen ini dalam border-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam border-box |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Menempatkan dalam susunan vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/overbar/#) | Menetapkan garis di atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/underbar/#) | Menetapkan garis di bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen persamaan atau contoh teks matematika lainnya.<br/>            Objek yang dikelilingi kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik perataan, <br/>            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| [`delimit(self, separator_character)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Membatasi argumen menggunakan karakter pembatas yang ditentukan |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)