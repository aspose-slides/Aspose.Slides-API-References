---
title: MathFraction class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathfraction/
---
## MathFraction kelas

Menentukan objek pecahan, yang terdiri dari pembilang dan penyebut yang dipisahkan oleh garis pecahan.
            Garis pecahan dapat berupa horizontal atau diagonal, tergantung pada properti pecahan.
            Objek pecahan juga digunakan untuk merepresentasikan fungsi stack, yang menempatkan satu elemen di atas elemen lain, tanpa garis pecahan.

**Inheritance:**[`MathFraction`](/slides/python-net/id/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathFraction mengekspos anggota-anggota berikut:

## Konstruktor

| Constructor | Description |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | Menginisialisasi MathFraction dengan pembilang, penyebut, dan tipe yang ditentukan |
| [`__init__(self, numerator, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | Menginisialisasi sebuah MathFraction tipe 'Bar' dengan pembilang dan penyebut yang ditentukan |

## Properti

| Property | Description |
| :- | :- |
| [`fraction_type`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/fraction_type/) | Tipe pecahan<br/>            Default: Bar |
| [`numerator`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/numerator/) | Pembilang |
| [`denominator`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/denominator/) | Penyebut |

## Metode

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/join/#imathelement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/join/#str) | Menggabungkan teks matematika dan membentuk blok matematika |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/divide/#imathelement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/divide/#str) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | Membuat pecahan dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/enclose/#) | Membungkus elemen matematika dalam tanda kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/enclose/#char-char) | Membungkus elemen matematika dalam karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/function/#imathelement) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/function/#str) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di sebelah kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/radical/#imathelement) | Menentukan akar matematika dengan tingkat yang diberikan dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/radical/#str) | Menentukan akar matematika dengan tingkat yang diberikan dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | Mengambil batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | Mengambil batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | Mengambil batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | Mengambil batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | Mengambil integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | Mengambil integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | Mengambil integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau karakter lain |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/to_border_box/#) | Menempatkan elemen ini dalam kotak batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/to_math_array/#) | Menempatkan dalam susunan vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/overbar/#) | Menetapkan bar di bagian atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/underbar/#) | Menetapkan bar di bagian bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen persamaan atau contoh lain dari teks matematika.<br/>            Objek yang dikotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik perataan, <br/>            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathfraction/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* kelas [`MathFraction`](/slides/python-net/id/aspose.slides.mathtext/mathfraction)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)