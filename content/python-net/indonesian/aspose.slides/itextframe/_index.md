---
title: ITextFrame class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/itextframe/
---
## ITextFrame kelas

Mewakili sebuah TextFrame.

Tipe ITextFrame mengekspos anggota-anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/id/aspose.slides/itextframe/paragraphs/) | Mengembalikan daftar semua paragraf dalam bingkai.<br/>            Baca-saja [`IParagraphCollection`](/slides/python-net/id/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/id/aspose.slides/itextframe/text/) | Mendapatkan atau mengatur teks biasa untuk TextFrame.<br/>            Baca/tulis **str**. |
| [`text_frame_format`](/slides/python-net/id/aspose.slides/itextframe/text_frame_format/) | Mengembalikan objek pemformatan untuk objek TextFrame ini.<br/>            Baca-saja [`ITextFrameFormat`](/slides/python-net/id/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/itextframe/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terkandung.<br/>            Baca-saja [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/id/aspose.slides/itextframe/parent_shape/) | Mengembalikan shape induk atau None jika objek induk tidak mengimplementasikan antarmuka IShape<br/>            Baca-saja [`IShape`](/slides/python-net/id/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/id/aspose.slides/itextframe/parent_cell/) | Mengembalikan sel induk atau None jika objek induk tidak mengimplementasikan antarmuka ICell.<br/>            Baca-saja [`ICell`](/slides/python-net/id/aspose.slides/icell). |
| [`slide`](/slides/python-net/id/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/itextframe/presentation/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/id/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/id/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/id/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/id/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/id/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama di semua paragraf. |
| [`split_text_by_columns(self)`](/slides/python-net/id/aspose.slides/itextframe/split_text_by_columns/#) | Membagi konten teks dari [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe) menjadi array string, <br/>            di mana setiap elemen sesuai dengan kolom teks terpisah dalam bingkai. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/id/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/id/aspose.slides/itextframe/replace_regex/#str-str) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)