---
title: MathBox class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathbox/
---
## MathBox kelas

Menentukan pengemasan logis (pengemasan) elemen matematis.
            Sebagai contoh, objek yang dibungkus dapat berfungsi sebagai emulator operator dengan atau tanpa titik penjajaran,
            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya.
            Sebagai contoh, operator "==" harus dibungkus untuk mencegah pemutusan baris.

**Pewarisan:**[`MathBox`](/slides/python-net/id/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathBox menampilkan anggota-anggota berikut:

## Konstruktor

| Constructor | Deskripsi |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Menginisialisasi MathBox dengan elemen yang ditentukan sebagai argumen |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`base`](/slides/python-net/id/aspose.slides.mathtext/mathbox/base/) | Argumen dasar |
| [`operator_emulator`](/slides/python-net/id/aspose.slides.mathtext/mathbox/operator_emulator/) | Emulator Operator.<br/>            Jika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. <br/>            Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemutus baris dan dapat disejajarkan dengan operator lain.<br/>            Emulator Operator sering digunakan ketika satu atau lebih glyph digabungkan menjadi sebuah operator, seperti '=='.<br/>            Nilai default: false |
| [`no_break`](/slides/python-net/id/aspose.slides.mathtext/mathbox/no_break/) | Tidak ada pemutusan<br/>            Properti ini menentukan properti "tidak dapat diputus" pada kotak objek. Jika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak.<br/>            Ini dapat penting bagi emulator operator yang terdiri dari lebih dari satu operator biner. <br/>            Jika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak.<br/>            Default: true |
| [`differential`](/slides/python-net/id/aspose.slides.mathtext/mathbox/differential/) | Diferensial<br/>            Jika true, kotak bertindak sebagai diferensial (mis., 𝑑𝑥 dalam integran), dan menerima jarak horizontal yang sesuai <br/>            jarak horizontal untuk diferensial matematis.<br/>            Default: false |
| [`alignment_point`](/slides/python-net/id/aspose.slides.mathtext/mathbox/alignment_point/) | Jika true, emulator operator ini berfungsi sebagai titik penjajaran; yaitu,<br/>            titik-titik penjajaran yang ditentukan dalam persamaan lain dapat disejajarkan dengan ini.<br/>            Default: false |
| [`explicit_break`](/slides/python-net/id/aspose.slides.mathtext/mathbox/explicit_break/) | Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box,<br/>            sehingga baris melipat pada awal objek kotak.<br/>            Menentukan nomor operator pada baris sebelumnya dari teks matematis yang akan<br/>            digunakan sebagai titik penjajaran untuk baris teks matematis saat ini<br/>            nilai yang mungkin: 1..255<br/>            Default: 0 (tidak ada pemutusan eksplisit) |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/join/#imathelement) | Menggabungkan elemen matematis dan membentuk blok matematis |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/join/#str) | Menggabungkan teks matematis dan membentuk blok matematis |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/divide/#imathelement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/divide/#str) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/enclose/#) | Membungkus elemen matematika dalam tanda kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/enclose/#char-char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/function/#imathelement) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/function/#str) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di sebelah kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/radical/#imathelement) | Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/radical/#str) | Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Mengambil batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Mengambil batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Mengambil batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Mengambil batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Mengambil integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Mengambil integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Mengambil integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau lainnya |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/to_border_box/#) | Menempatkan elemen ini dalam kotak batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/to_math_array/#) | Menempatkan dalam array vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/overbar/#) | Menetapkan garis pada bagian atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/underbar/#) | Menetapkan garis pada bagian bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen suatu persamaan atau contoh lain dari teks matematis.<br/>            Objek yang dibungkus dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penjajaran, <br/>            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya. |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathbox/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathBox`](/slides/python-net/id/aspose.slides.mathtext/mathbox)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)