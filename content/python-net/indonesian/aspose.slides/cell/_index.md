---
title: Cell class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/cell/
---
## Kelas Cell

Mewakili sebuah sel dalam tabel.

Tipe Cell menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`offset_x`](/slides/python-net/id/aspose.slides/cell/offset_x/) | Mengembalikan jarak dari sisi kiri tabel ke sisi kiri sel.<br/>            Hanya-baca **float**. |
| [`offset_y`](/slides/python-net/id/aspose.slides/cell/offset_y/) | Mengembalikan jarak dari sisi atas tabel ke sisi atas sel.<br/>            Hanya-baca **float**. |
| [`first_row_index`](/slides/python-net/id/aspose.slides/cell/first_row_index/) | Mengembalikan indeks baris pertama yang dicakup oleh sel.<br/>            Hanya-baca **int**. |
| [`first_column_index`](/slides/python-net/id/aspose.slides/cell/first_column_index/) | Mengembalikan indeks kolom pertama yang dicakup oleh sel.<br/>            Hanya-baca **int**. |
| [`width`](/slides/python-net/id/aspose.slides/cell/width/) | Mengembalikan lebar sel.<br/>            Hanya-baca **float**. |
| [`height`](/slides/python-net/id/aspose.slides/cell/height/) | Mengembalikan tinggi sel.<br/>            Hanya-baca **float**. |
| [`minimal_height`](/slides/python-net/id/aspose.slides/cell/minimal_height/) | Mengembalikan tinggi minimum sebuah sel.<br/>            Ini adalah jumlah tinggi minimal semua baris yang dicakup oleh sel.<br/>            Hanya-baca **float**. |
| [`margin_left`](/slides/python-net/id/aspose.slides/cell/margin_left/) | Mengembalikan atau mengatur margin kiri dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_right`](/slides/python-net/id/aspose.slides/cell/margin_right/) | Mengembalikan atau mengatur margin kanan dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_top`](/slides/python-net/id/aspose.slides/cell/margin_top/) | Mengembalikan atau mengatur margin atas dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_bottom`](/slides/python-net/id/aspose.slides/cell/margin_bottom/) | Mengembalikan atau mengatur margin bawah dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`text_vertical_type`](/slides/python-net/id/aspose.slides/cell/text_vertical_type/) | Mengembalikan atau mengatur jenis teks vertikal.<br/>            Baca/tulis [`TextVerticalType`](/slides/python-net/id/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/id/aspose.slides/cell/text_anchor_type/) | Mengembalikan atau mengatur jenis jangkar teks.<br/>            Baca/tulis [`TextAnchorType`](/slides/python-net/id/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/id/aspose.slides/cell/anchor_center/) | Menentukan apakah kotak teks berada di tengah sel atau tidak.<br/>            Baca/tulis **bool**. |
| [`first_row`](/slides/python-net/id/aspose.slides/cell/first_row/) | Mendapatkan baris pertama sel.<br/>            Hanya-baca [`IRow`](/slides/python-net/id/aspose.slides/irow). |
| [`first_column`](/slides/python-net/id/aspose.slides/cell/first_column/) | Mendapatkan kolom pertama sel.<br/>            Hanya-baca [`IColumn`](/slides/python-net/id/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/id/aspose.slides/cell/col_span/) | Mengembalikan jumlah kolom grid dalam tabel induk yang akan dicakup oleh sel saat ini. Properti ini memungkinkan sel memiliki tampilan seolah-olah digabung, karena mereka melintasi batas vertikal sel lain dalam tabel.<br/>            Hanya-baca **int**. |
| [`row_span`](/slides/python-net/id/aspose.slides/cell/row_span/) | Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. Ini digunakan bersama atribut vMerge pada sel lain untuk menentukan sel awal penggabungan horizontal.<br/>            Hanya-baca **int**. |
| [`text_frame`](/slides/python-net/id/aspose.slides/cell/text_frame/) | Mengembalikan frame teks dari sebuah sel.<br/>            Hanya-baca [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`table`](/slides/python-net/id/aspose.slides/cell/table/) | Mengembalikan objek Table induk untuk sebuah sel.<br/>            Hanya-baca [`ITable`](/slides/python-net/id/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/id/aspose.slides/cell/is_merged_cell/) | Mengembalikan true bila sel digabung dengan sel lain yang disesuaikan, false jika tidak.<br/>            Hanya-baca **bool**. |
| [`cell_format`](/slides/python-net/id/aspose.slides/cell/cell_format/) | Mengembalikan objek CellFormat yang berisi properti pemformatan untuk sel ini.<br/>            Hanya-baca [`ICellFormat`](/slides/python-net/id/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/id/aspose.slides/cell/slide/) | Mengembalikan slide induk dari sebuah sel.<br/>            Hanya-baca [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/cell/presentation/) | Mengembalikan presentasi induk dari sebuah sel.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/id/aspose.slides/cell/split_by_col_span/#int) | Membagi sel menjadi dua sel berdasarkan indeks kolom. |
| [`split_by_row_span(self, index)`](/slides/python-net/id/aspose.slides/cell/split_by_row_span/#int) | Membagi sel menjadi dua sel berdasarkan indeks baris. |
| [`split_by_height(self, height)`](/slides/python-net/id/aspose.slides/cell/split_by_height/#float) | Membagi sel berdasarkan tinggi. |
| [`split_by_width(self, width)`](/slides/python-net/id/aspose.slides/cell/split_by_width/#float) | Membagi sel berdasarkan lebar. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)