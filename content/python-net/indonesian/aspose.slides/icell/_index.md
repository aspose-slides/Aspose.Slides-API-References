---
title: ICell class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/icell/
---
## ICell kelas

Mewakili sel dalam sebuah tabel.

Tipe ICell menyediakan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`offset_x`](/slides/python-net/id/aspose.slides/icell/offset_x/) | Mengembalikan jarak dari sisi kiri tabel ke sisi kiri sel.<br/>            Hanya-baca **float**. |
| [`offset_y`](/slides/python-net/id/aspose.slides/icell/offset_y/) | Mengembalikan jarak dari sisi atas tabel ke sisi atas sel.<br/>            Hanya-baca **float**. |
| [`first_row_index`](/slides/python-net/id/aspose.slides/icell/first_row_index/) | Mengembalikan indeks baris pertama yang dicakup oleh sel.<br/>            Hanya-baca **int**. |
| [`first_column_index`](/slides/python-net/id/aspose.slides/icell/first_column_index/) | Mengembalikan indeks kolom pertama yang dicakup oleh sel.<br/>            Hanya-baca **int**. |
| [`width`](/slides/python-net/id/aspose.slides/icell/width/) | Mengembalikan lebar sel.<br/>            Hanya-baca **float**. |
| [`height`](/slides/python-net/id/aspose.slides/icell/height/) | Mengembalikan tinggi sel.<br/>            Hanya-baca **float**. |
| [`minimal_height`](/slides/python-net/id/aspose.slides/icell/minimal_height/) | Mengembalikan tinggi minimum sel.<br/>            Ini adalah jumlah tinggi minimal semua baris yang ditutupi oleh sel.<br/>            Hanya-baca **float**. |
| [`margin_left`](/slides/python-net/id/aspose.slides/icell/margin_left/) | Mengembalikan atau mengatur margin kiri dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_right`](/slides/python-net/id/aspose.slides/icell/margin_right/) | Mengembalikan atau mengatur margin kanan dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_top`](/slides/python-net/id/aspose.slides/icell/margin_top/) | Mengembalikan atau mengatur margin atas dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_bottom`](/slides/python-net/id/aspose.slides/icell/margin_bottom/) | Mengembalikan atau mengatur margin bawah dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`text_vertical_type`](/slides/python-net/id/aspose.slides/icell/text_vertical_type/) | Mengembalikan atau mengatur tipe teks vertikal.<br/>            Baca/tulis [`TextVerticalType`](/slides/python-net/id/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/id/aspose.slides/icell/text_anchor_type/) | Mengembalikan atau mengatur tipe jangkar teks.<br/>            Baca/tulis [`TextAnchorType`](/slides/python-net/id/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/id/aspose.slides/icell/anchor_center/) | Menentukan apakah kotak teks terpusat di dalam sel atau tidak.<br/>            Baca/tulis **bool**. |
| [`first_column`](/slides/python-net/id/aspose.slides/icell/first_column/) | Mendapatkan kolom pertama sel.<br/>            Hanya-baca [`IColumn`](/slides/python-net/id/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/id/aspose.slides/icell/first_row/) | Mendapatkan baris pertama sel.<br/>            Hanya-baca [`IRow`](/slides/python-net/id/aspose.slides/irow). |
| [`col_span`](/slides/python-net/id/aspose.slides/icell/col_span/) | Mengembalikan jumlah kolom grid dalam grid tabel induk yang akan dilalui oleh sel saat ini. Properti ini memungkinkan sel memiliki tampilan seolah-olah digabung, karena mereka melewati batas vertikal sel lain dalam tabel.<br/>            Hanya-baca **int**. |
| [`row_span`](/slides/python-net/id/aspose.slides/icell/row_span/) | Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. Ini digunakan bersama atribut vMerge pada sel lain untuk menentukan sel awal penggabungan horizontal.<br/>            Hanya-baca **int**. |
| [`text_frame`](/slides/python-net/id/aspose.slides/icell/text_frame/) | Mengembalikan frame teks sel.<br/>            Hanya-baca [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`table`](/slides/python-net/id/aspose.slides/icell/table/) | Mengembalikan objek Table induk untuk sel.<br/>            Hanya-baca [`ITable`](/slides/python-net/id/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/id/aspose.slides/icell/is_merged_cell/) | Mengembalikan true jika sel digabung dengan sel yang disesuaikan, false jika tidak.<br/>            Hanya-baca **bool**. |
| [`cell_format`](/slides/python-net/id/aspose.slides/icell/cell_format/) | Mengembalikan objek CellFormat yang berisi properti pemformatan untuk sel ini.<br/>            Hanya-baca [`ICellFormat`](/slides/python-net/id/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/id/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/icell/presentation/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/id/aspose.slides/icell/split_by_col_span/#int) | Memisahkan sel menjadi dua sel berdasarkan indeks kolom. |
| [`split_by_row_span(self, index)`](/slides/python-net/id/aspose.slides/icell/split_by_row_span/#int) | Memisahkan sel menjadi dua sel berdasarkan indeks baris. |
| [`split_by_height(self, height)`](/slides/python-net/id/aspose.slides/icell/split_by_height/#float) | Memisahkan sel berdasarkan tinggi. |
| [`split_by_width(self, width)`](/slides/python-net/id/aspose.slides/icell/split_by_width/#float) | Memisahkan sel berdasarkan lebar. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)