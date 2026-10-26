---
title: Hyperlink class
second_title: Aspose.Slides untuk Python via Referensi API .NET
description: 
type: docs
url: /id/aspose.slides/hyperlink/
---
## Kelas Hyperlink

Mewakili sebuah hyperlink.

**Pewarisan:**[`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/id/aspose.slides/pviobject)

Tipe Hyperlink menampilkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/id/aspose.slides/hyperlink/__init__/#str) | Membuat sebuah instance dari hyperlink. |
| [`__init__(self, slide)`](/slides/python-net/id/aspose.slides/hyperlink/__init__/#islide) | Membuat sebuah instance dari hyperlink yang mengarah ke slide tertentu.<br/>            Catatan: hyperlink yang dibuat harus ditetapkan ke objek tertentu dalam presentasi yang sama, jika tidak tautan akan disimpan sebagai NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/id/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Membuat sebuah instance dari hyperlink menggunakan hyperlink lain sebagai sumber, menimpa properti sekunder. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`no_action`](/slides/python-net/id/aspose.slides/hyperlink/no_action/) | Mengembalikan sebuah hyperlink khusus "do nothing".<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/id/aspose.slides/hyperlink/media/) | Mengembalikan sebuah hyperlink khusus "play mediafile". Digunakan dalam AudioFrame dan VideoFrame.<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/id/aspose.slides/hyperlink/next_slide/) | Mengembalikan hyperlink ke slide berikutnya.<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/id/aspose.slides/hyperlink/previous_slide/) | Mengembalikan hyperlink ke slide sebelumnya.<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/id/aspose.slides/hyperlink/first_slide/) | Mengembalikan hyperlink ke slide pertama dalam presentasi.<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/id/aspose.slides/hyperlink/last_slide/) | Mengembalikan hyperlink ke slide terakhir dalam presentasi.<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/id/aspose.slides/hyperlink/last_vieved_slide/) | Mengembalikan hyperlink ke slide yang terakhir dilihat.<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/id/aspose.slides/hyperlink/end_show/) | Mengembalikan hyperlink yang mengakhiri pertunjukan.<br/>            Baca-saja [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/id/aspose.slides/hyperlink/action_type/) | Mengembalikan tipe aksi Hyperlink.<br/>            Baca-saja [`HyperlinkActionType`](/slides/python-net/id/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/id/aspose.slides/hyperlink/external_url/) | Menentukan URL eksternal.<br/>            Baca-saja **str**. |
| [`target_slide`](/slides/python-net/id/aspose.slides/hyperlink/target_slide/) | Jika Hyperlink menargetkan slide tertentu, mengembalikan slide tersebut.<br/>            Baca-saja [`ISlide`](/slides/python-net/id/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/id/aspose.slides/hyperlink/external_url_original/) | Mewakili sebuah hyperlink yang ditetapkan untuk bagian ini tanpa memperhatikan konten sebenarnya dari bagian tersebut.<br/>            <br/>            PowerPoint berperilaku khusus untuk tautan dan teks yang bersesuaian dalam sebuah bagian. Ini memungkinkan pembuatan teks untuk hyperlink dalam bentuk URL yang valid, berbeda dari alamat asli tautan. Dalam hal ini, ketika Anda melihat tautan di jendela edit, tautan akan diubah agar sesuai dengan bagian teks. Properti ini mewakili nilai asli dari hyperlink. |
| [`target_frame`](/slides/python-net/id/aspose.slides/hyperlink/target_frame/) | Mengembalikan frame dalam frameset HTML induk untuk target tautan induk ketika ada.<br/>            Baca/tulis **str**. |
| [`tooltip`](/slides/python-net/id/aspose.slides/hyperlink/tooltip/) | Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna<br/>            sebagai yang terkait dengan tautan induk.<br/>            Baca/tulis **str**. |
| [`history`](/slides/python-net/id/aspose.slides/hyperlink/history/) | Menentukan apakah target tautan induk akan ditambahkan<br/>            ke daftar tautan yang telah dilihat ketika dipanggil.<br/>            Baca/tulis **bool**. |
| [`highlight_click`](/slides/python-net/id/aspose.slides/hyperlink/highlight_click/) | Menentukan apakah hyperlink harus disorot saat diklik.<br/>            Baca/tulis **bool**. |
| [`stop_sound_on_click`](/slides/python-net/id/aspose.slides/hyperlink/stop_sound_on_click/) | Menentukan apakah suara harus dihentikan saat hyperlink diklik.<br/>            Baca/tulis **bool**. |
| [`sound`](/slides/python-net/id/aspose.slides/hyperlink/sound/) | Mewakili suara yang sedang diputar oleh hyperlink.<br/>            Baca/tulis [`IAudio`](/slides/python-net/id/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/id/aspose.slides/hyperlink/color_source/) | Mewakili sumber warna hyperlink - baik gaya maupun format bagian.<br/>            Baca/tulis [`HyperlinkColorSource`](/slides/python-net/id/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/id/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/hyperlink/presentation/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/id/aspose.slides/hyperlink/equals/#ihyperlink) | Menentukan apakah dua instance Hyperlink sama. |

### Lihat Juga
* kelas [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink)
* kelas [`PVIObject`](/slides/python-net/id/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)