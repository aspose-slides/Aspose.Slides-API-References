---
title: MathBorderBox class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox kelas

Menggambar batas berbentuk persegi panjang atau bentuk lainnya di sekitar IMathElement.

**Warisan:**[`MathBorderBox`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathBorderBox mengekspos anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Membuat elemen MathBorderBox dengan batas persegi panjang |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Membuat elemen MathBorderBox |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`base`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/base/) | Argumen dasar |
| [`hide_top`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/hide_top/) | Sembunyikan Tepi Atas (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi atas kotak batas. |
| [`hide_bottom`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Sembunyikan Tepi Bawah (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi bawah kotak batas. |
| [`hide_left`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/hide_left/) | Sembunyikan Tepi Kiri (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kiri kotak batas. |
| [`hide_right`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/hide_right/) | Sembunyikan Tepi Kanan (default false) - menentukan keadaan tersembunyi atau terlihat dari tepi kanan kotak batas. |
| [`strikethrough_horizontal`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Coret Horizontal (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret horizontal. |
| [`strikethrough_vertical`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Coret Vertikal (default false) - menentukan keadaan tersembunyi atau terlihat dari garis coret vertikal. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Coret Diagonal Kiri-Bawah ke Kanan-Atas (default false).<br/>            Menentukan keadaan tersembunyi atau terlihat dari garis coret diagonal dari sudut kiri-bawah ke sudut kanan-atas kotak batas. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Coret Diagonal Kiri-Atas ke Kanan-Bawah (default false).<br/>            Menentukan keadaan tersembunyi atau terlihat dari garis coret diagonal dari sudut kiri-atas ke sudut kanan-bawah kotak batas. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/join/#str) | Menggabungkan teks matematika dan membentuk blok matematika |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/divide/#str) | Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Membuat fraksi tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Membuat fraksi tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/enclose/#) | Membungkus elemen matematika dalam tanda kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Membungkus elemen matematika dengan karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/function/#str) | Mengambil fungsi dari sebuah argumen dengan menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Mengambil fungsi tertentu dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Mengambil fungsi tertentu dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Mengambil fungsi tertentu dengan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Mengambil fungsi tertentu dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Mengambil fungsi tertentu dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/radical/#str) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Mengambil batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Mengambil batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Mengambil batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Mengambil batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Mengambil integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Mengambil integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Mengambil integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau lainnya |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Menempatkan elemen ini dalam kotak-batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak-batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Menempatkan dalam larik vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/overbar/#) | Menetapkan garis di atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/underbar/#) | Menetapkan garis di bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen sebuah persamaan atau contoh teks matematika lainnya.<br/>            Sebuah objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, <br/>            berfungsi sebagai titik pemutusan baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya. |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathBorderBox`](/slides/python-net/id/aspose.slides.mathtext/mathborderbox)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* pustaka [`Aspose.Slides`](/slides/python-net)