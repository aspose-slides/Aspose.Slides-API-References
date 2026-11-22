---
title: MathDelimiter class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter kelas

Menentukan objek delimiter, yang terdiri dari karakter pembuka dan penutup (seperti kurung, kurung kurawal, kurung siku, dan batang vertikal), dan satu atau lebih elemen matematika di dalamnya, dipisahkan oleh karakter tertentu. Contoh: (𝑥2); [𝑥2|𝑦2]

**Pewarisan:**[`MathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathDelimiter mengekspos anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Menginisialisasi MathDelimiter dengan elemen yang ditentukan sebagai argumen basis tunggal |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`arguments`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/arguments/) | Satu atau lebih elemen matematika yang dipisahkan oleh karakter delimiter |
| [`beginning_character`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character menentukan karakter delimiter awal, atau pembuka. <br/>            Delimiter matematika adalah karakter pembungkus seperti kurung, kurung siku, dan kurung kurawal.<br/>            Nilai default: '('. |
| [`separator_character`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. <br/>            Nilai default: '\|'. |
| [`ending_character`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character menentukan karakter delimiter akhir, atau penutup. <br/>            Delimiter matematika adalah karakter pembungkus seperti kurung, kurung siku, dan kurung kurawal.<br/>            Nilai default: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya.<br/>            Nilai default adalah true. |
| [`delimiter_shape`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Menentukan bentuk delimiter dalam objek delimiter. <br/>            Ketika MathDelimiterShape.Centered, delimiter berada di tengah sumbu matematika dari teks matematika <br/>            dan masih dapat disesuaikan untuk menutupi seluruh tinggi kontennya.<br/>            Ketika MathDelimiterShape.Match, tinggi dan bentuknya diubah agar persis cocok dengan kontennya. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/join/#str) | Menggabungkan teks matematika dan membentuk blok matematika |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#str) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/enclose/#) | Membungkus elemen matematika dalam kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Membungkus elemen matematika dalam karakter tertentu seperti kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Menerima fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/function/#str) | Menerima fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Menerima fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/radical/#str) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Menerima batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Menerima batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Menerima batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Menerima batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Menerima integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Menerima integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Menerima integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Menerima integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Menerima integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau lainnya |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Menempatkan elemen ini dalam kotak-batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak-batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Menempatkan dalam array vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/overbar/#) | Menetapkan garis di atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/underbar/#) | Menetapkan garis di bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen sebuah persamaan atau contoh teks matematika lainnya.<br/>            Objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penjajaran, <br/>            berfungsi sebagai titik putus baris, atau dikelompokkan sehingga tidak mengizinkan putus baris di dalamnya. |
| [`delimit(self, separator_character)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Membatasi argumen menggunakan karakter delimiter yang ditentukan |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* pustaka [`Aspose.Slides`](/slides/python-net)