---
title: TextFrame class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/textframe/
---
## TextFrame kelas

Represents a TextFrame.

The TextFrame type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`paragraphs`](/slides/python-net/id/aspose.slides/textframe/paragraphs/) | Mengembalikan daftar semua paragraf dalam sebuah frame.<br/>            Baca-saja [`IParagraphCollection`](/slides/python-net/id/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/id/aspose.slides/textframe/text/) | Mengambil atau mengatur teks biasa untuk TextFrame.<br/>            Baca/tulis **str**. |
| [`text_frame_format`](/slides/python-net/id/aspose.slides/textframe/text_frame_format/) | Mengembalikan objek format untuk objek TextFrame ini.<br/>            Baca-saja [`ITextFrameFormat`](/slides/python-net/id/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/textframe/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terdapat di dalamnya.<br/>            Baca-saja [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/id/aspose.slides/textframe/slide/) | Mengembalikan slide induk dari sebuah TextFrame.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/textframe/presentation/) | Mengembalikan presentasi induk dari sebuah TextFrame.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/id/aspose.slides/textframe/parent_shape/) | Mengembalikan shape induk atau None jika objek induk tidak mengimplementasikan antarmuka IShape<br/>            Baca-saja [`IShape`](/slides/python-net/id/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/id/aspose.slides/textframe/parent_cell/) | Mengembalikan sel induk atau None jika objek induk tidak mengimplementasikan antarmuka ICell.<br/>            Baca-saja [`ICell`](/slides/python-net/id/aspose.slides/icell). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/id/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/id/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/id/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/id/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/id/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/textframe/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama di semua paragraf. |
| [`split_text_by_columns(self)`](/slides/python-net/id/aspose.slides/textframe/split_text_by_columns/#) | Membagi konten teks dari [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe) menjadi array string, <br/>            di mana setiap elemen sesuai dengan kolom teks terpisah dalam frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/id/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/id/aspose.slides/textframe/replace_regex/#str-str) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)