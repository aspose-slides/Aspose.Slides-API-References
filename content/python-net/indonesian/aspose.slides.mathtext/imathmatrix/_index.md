---
title: IMathMatrix class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix kelas

Menetapkan objek Matrix, yang terdiri dari elemen anak yang disusun dalam satu atau beberapa baris dan kolom. 
            Penting untuk dicatat bahwa matriks tidak memiliki pembatas bawaan. 
            Untuk menempatkan matriks dalam kurung, Anda harus menggunakan objek delimiter (IMathDelimiter).
            Argumen null dapat digunakan untuk membuat celah dalam matriks.

Tipe IMathMatrix menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`row_count`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/row_count/) | Jumlah baris dalam matriks |
| [`column_count`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/column_count/) | Jumlah kolom dalam matriks |
| [`hide_placeholders`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Sembunyikan placeholder untuk elemen matriks kosong<br/>            Bawaan: false |
| [`base_justification`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/base_justification/) | Menentukan perataan vertikal terhadap teks di sekitarnya. <br/>            Nilai yang mungkin adalah top, bottom, dan center.<br/>            Bawaan: Center |
| [`min_column_width`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/min_column_width/) | Lebar kolom minimum dalam twips (1/20 poin)<br/>            Jarak celah (juga disebut “Column Gap” atau “Gap Width”) ditambahkan ke <br/>            MinColumnWidth untuk menentukan Total Spasi Kolom Matriks<br/>            (jarak antara tepi yang sama dari kolom yang berbeda).<br/>            Bawaan: 0. |
| [`column_gap_rule`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Jenis spasi horizontal antara kolom matriks; <br/>            Satuan spasi horizontal dapat berupa em atau poin (disimpan sebagai twips).<br/>            Bawaan: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/column_gap/) | Nilai spasi horizontal antara kolom matriks;<br/>            Jika ColumnGapRule diatur ke 3 ("Exactly"), maka satuan diartikan sebagai twips (1/20 poin)<br/>            Jika ColumnGapRule diatur ke 4 ("Multiple"), maka satuan diartikan sebagai jumlah kenaikan 0.5 em.<br/>            Pada kasus lain diabaikan.<br/>            Bawaan: 0 |
| [`row_gap_rule`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Jenis spasi vertikal antara baris matriks; <br/>            Satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twips).<br/>            Bawaan: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/row_gap/) | Nilai spasi vertikal antara baris matriks;<br/>            Jika RowGapRule diatur ke 3 ("Exactly"), maka satuan diartikan sebagai twips (1/20 poin)<br/>            Jika RowGapRule diatur ke 4 ("Multiple"), maka satuan diartikan sebagai setengah baris.<br/>            Bawaan: 0 |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Dapatkan perataan horizontal dari kolom yang ditentukan |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Atur perataan horizontal dari kolom yang ditentukan |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Atur perataan horizontal dari kolom-kolom yang ditentukan |
| [`insert_row_before(self, row_index)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Sisipkan baris baru sebelum yang ditentukan<br/>            Pada awalnya semua elemen di baris baru adalah None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Sisipkan baris baru setelah yang ditentukan<br/>            Pada awalnya semua elemen di baris baru adalah None. |
| [`delete_row(self, row_index)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Menghapus baris yang ditentukan |
| [`insert_column_before(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Sisipkan kolom baru sebelum yang ditentukan<br/>            Pada awalnya semua elemen di kolom baru adalah None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Sisipkan kolom baru setelah yang ditentukan<br/>            Pada awalnya semua elemen di kolom baru adalah None. |
| [`delete_column(self, column_index)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Menghapus kolom yang ditentukan |
| [`get_children(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/id/aspose.slides.mathtext/imathmatrix/to_box/#) |  |


### Lihat Juga
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)