---
title: MathBlock class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathblock/
---
## MathBlock kelas

Menentukan sebuah instance teks matematika yang berada dalam MathParagraph dan mulai pada barisnya sendiri.
            Semua zona matematika, termasuk persamaan, ekspresi, kumpulan persamaan atau ekspresi, dan formula direpresentasikan oleh blok matematika.

**Inheritance:**[`MathBlock`](/slides/python-net/id/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/__init__/#) | Menginisialisasi sebuah instance baru dari kelas MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Membuat blok matematika baru dan menempatkan elemen yang ditentukan di dalamnya |
| [`__init__(self, math_elements)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`count`](/slides/python-net/id/aspose.slides.mathtext/mathblock/count/) | Mendapatkan jumlah elemen matematika anak yang sebenarnya terkandung dalam koleksi.<br/>            Hanya-baca **int**. |
| [`is_read_only`](/slides/python-net/id/aspose.slides.mathtext/mathblock/is_read_only/) | Mengembalikan false karena koleksi elemen anak dapat dimodifikasi. |

Mendapatkan atau mengatur IMathElement pada indeks yang ditentukan.

## Indeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.mathtext/mathblock/__getitem__/) | Indeks berbasis nol dari item |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/join/#imathelement) | Menggabungkan elemen matematika dengan blok matematika ini |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/join/#str) | Menggabungkan teks matematika dengan blok matematika ini |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/divide/#imathelement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/divide/#str) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Membuat pecahan tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Membuat pecahan tipe yang ditentukan dengan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/enclose/#char-char) | Membungkus elemen anak dari blok ini dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Membungkus elemen anak dari blok ini dalam karakter yang ditentukan seperti tanda kurung atau lain sebagai bingkai<br/>            dan memisahkan dengan karakter pemisah |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/enclose/#) | Membungkus sebuah elemen matematika dalam tanda kurung |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/function/#imathelement) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/function/#str) | Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Mengambil fungsi yang ditentukan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di sebelah kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/radical/#imathelement) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/radical/#str) | Menentukan akar matematika dengan pangkat yang diberikan dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Mengambil batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Mengambil batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Mengambil batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Mengambil batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Mengambil integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Mengambil integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Mengambil integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompok seperti kurung kurawal bawah atau lain |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/to_border_box/#) | Menempatkan elemen ini dalam kotak batas |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak batas |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/to_math_array/#) | Menempatkan elemen anak dalam susunan vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/overbar/#) | Menetapkan bar di atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/underbar/#) | Menetapkan bar di bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen sebuah persamaan atau contoh teks matematika lainnya.<br/>            Objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, <br/>            berfungsi sebagai titik jeda baris, atau dikelompokkan sehingga tidak mengizinkan jeda baris di dalamnya. |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/get_children/#) | Mendapatkan elemen anak |
| [`add(self, item)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/add/#imathelement) | Menambahkan elemen matematika ke akhir koleksi. |
| [`clear(self)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/clear/#) | Menghapus semua elemen dari koleksi. |
| [`contains(self, item)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/contains/#imathelement) | Menentukan apakah koleksi berisi nilai tertentu. |
| [`copy_to(self, array, array_index)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Menyalin ke array yang ditentukan. |
| [`remove(self, item)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/remove/#imathelement) | Menghapus kejadian pertama dari objek tertentu dalam koleksi. |
| [`index_of(self, item)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Menentukan indeks dari elemen matematika tertentu dalam koleksi. |
| [`insert(self, index, item)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Menyisipkan MathElement ke dalam koleksi pada indeks yang ditentukan. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/remove_at/#int) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [`join_block(self, other)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Menggabungkan blok matematika lain dengan yang ini |
| [`delimit(self, separator_character)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/delimit/#char) | Membatasi elemen anak dengan karakter pemisah (tanpa kurung) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/id/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Menyimpan konten [`MathBlock`](/slides/python-net/id/aspose.slides.mathtext/mathblock) ini sebagai MathML |

### Lihat Juga
* kelas [`MathBlock`](/slides/python-net/id/aspose.slides.mathtext/mathblock)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* pustaka [`Aspose.Slides`](/slides/python-net)