---
title: MathMatrix class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix kelas

Menentukan objek Matrix, yang terdiri dari elemen anak yang disusun dalam satu atau beberapa baris dan kolom. Penting untuk dicatat bahwa matriks tidak memiliki pembatas bawaan. Untuk menempatkan matriks dalam tanda kurung, Anda harus menggunakan objek delimiter (IMathDelimiter). Argumen null dapat digunakan untuk membuat celah dalam matriks.

**Pewarisan:**[`MathMatrix`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)

Tipe MathMatrix mengekspos anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Menginisialisasi instance baru dari kelas MathMatrix. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`row_count`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/row_count/) | Jumlah baris dalam matriks |
| [`column_count`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/column_count/) | Jumlah kolom dalam matriks |
| [`hide_placeholders`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Sembunyikan placeholder untuk elemen matriks kosong<br/>            Default: false |
| [`base_justification`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/base_justification/) | Menentukan perataan vertikal relatif terhadap teks di sekitarnya.<br/>            Nilai yang memungkinkan adalah top, bottom, dan center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/min_column_width/) | Lebar kolom minimum dalam twips (1/20 poin)<br/>            Jarak celah (juga disebut “Column Gap” atau “Gap Width”) ditambahkan ke <br/>            MinColumnWidth untuk menentukan total Matrix Column Spacing<br/>            (jarak antara tepi yang sama dari kolom yang berbeda).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Jenis jarak horizontal antara kolom matriks; <br/>            Unit jarak horizontal dapat berupa ems atau points (disimpan sebagai twips).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/column_gap/) | Nilai jarak horizontal antara kolom matriks;<br/>            Jika ColumnGapRule diatur ke 3 ("Exactly"), maka unit diartikan sebagai twips (1/20 poin)<br/>            Jika ColumnGapRule diatur ke 4 ("Multiple"), maka unit diartikan sebagai jumlah kenaikan 0,5 em.<br/>            Pada kasus lain diabaikan.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Jenis jarak vertikal antara baris matriks; <br/>            Unit jarak vertikal dapat berupa lines atau points (disimpan sebagai twips).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/row_gap/) | Nilai jarak vertikal antara baris matriks;<br/>            Jika RowGapRule diatur ke 3 ("Exactly"), maka unit diartikan sebagai twips (1/20 poin)<br/>            Jika RowGapRule diatur ke 4 ("Multiple"), maka unit diartikan sebagai setengah baris.<br/>            Default: 0 |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Menggabungkan elemen matematika dan membentuk blok matematika |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/join/#str) | Menggabungkan teks matematika dan membentuk blok matematika |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/divide/#str) | Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/enclose/#) | Membungkus elemen matematika dalam tanda kurung |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Mengambil fungsi dengan argumen menggunakan instance ini sebagai nama fungsi |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/function/#str) | Mengambil fungsi dengan argumen menggunakan instance ini sebagai nama fungsi |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Mengambil fungsi tertentu menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Membuat subskrip |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Membuat subskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Membuat superskrip |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Membuat superskrip |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Membuat subskrip dan superskrip di sebelah kanan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Membuat subskrip dan superskrip di sebelah kiri |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Membuat subskrip dan superskrip di sebelah kiri |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/radical/#str) | Menentukan akar matematika dengan pangkat tertentu dari argumen yang ditentukan. |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Mengambil batas atas |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Mengambil batas atas |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Mengambil batas bawah |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Mengambil batas bawah |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Membuat operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Membuat operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Mengambil integral |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Mengambil integral tanpa batas |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Mengambil integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Mengambil integral |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/group/#) | Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau yang lain |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Menempatkan elemen ini dalam kotak-border |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Menempatkan elemen ini dalam kotak-border |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Menempatkan dalam susunan vertikal |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/accent/#char) | Menetapkan tanda aksen (karakter di atas elemen ini) |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/overbar/#) | Menetapkan bar di atas elemen ini |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/underbar/#) | Menetapkan bar di bawah elemen ini |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/to_box/#) | Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) <br/>            yang digunakan untuk mengelompokkan komponen suatu persamaan atau contoh teks matematika lainnya.<br/>            Objek berkotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik perataan, <br/>            berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Mendapatkan perataan horizontal dari kolom yang ditentukan |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Mengatur perataan horizontal dari kolom yang ditentukan |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Mengatur perataan horizontal dari kolom-kolom yang ditentukan |
| [`insert_row_before(self, row_index)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Menyisipkan baris baru sebelum yang ditentukan<br/>            Awalnya semua elemen di baris baru adalah None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Menyisipkan baris baru setelah yang ditentukan<br/>            Awalnya semua elemen di baris baru adalah None. |
| [`delete_row(self, row_index)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Menghapus baris yang ditentukan |
| [`insert_column_before(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Menyisipkan kolom baru sebelum yang ditentukan<br/>            Awalnya semua elemen di kolom baru adalah None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Menyisipkan kolom baru setelah yang ditentukan<br/>            Awalnya semua elemen di kolom baru adalah None. |
| [`delete_column(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Menghapus kolom yang ditentukan |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix/get_children/#) | Mendapatkan elemen anak |

### Lihat Juga
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* kelas [`MathMatrix`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)