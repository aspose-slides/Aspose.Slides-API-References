---
title: IHyperlink class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ihyperlink/
---
## Kelas IHyperlink

Mewakili hyperlink.

Tipe IHyperlink menyajikan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`action_type`](/slides/python-net/id/aspose.slides/ihyperlink/action_type/) | Mengembalikan tipe aksi HyperLinkEx.<br/>            Hanya-baca [`HyperlinkActionType`](/slides/python-net/id/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/id/aspose.slides/ihyperlink/external_url/) | Menentukan URL eksternal<br/>            Jika properti ini menjadi bukan None maka properti TargetSlide menjadi None.<br/>            Hanya-baca **str**. |
| [`external_url_original`](/slides/python-net/id/aspose.slides/ihyperlink/external_url_original/) | Menrepresentasikan hyperlink yang ditetapkan untuk bagian ini tanpa memperhatikan konten sebenarnya dari bagian tersebut.<br/>            <br/>            PowerPoint berperilaku khusus untuk tautan dan teks terkaitnya dalam sebuah bagian. Ini memungkinkan membuat teks untuk hyperlink dalam<br/>            bentuk URL yang valid, berbeda dari alamat sebenarnya dari tautan. Dalam kasus ini, ketika Anda melihat tautan di jendela edit, itu akan<br/>            diubah untuk mencocokkan bagian teks. Properti ini merepresentasikan nilai asli hyperlink. |
| [`target_slide`](/slides/python-net/id/aspose.slides/ihyperlink/target_slide/) | Jika HyperlinkEx menargetkan slide tertentu, mengembalikan slide ini.<br/>            Jika properti menjadi bukan None maka properti ExternalUrl menjadi None.<br/>            Hanya-baca [`ISlide`](/slides/python-net/id/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/id/aspose.slides/ihyperlink/target_frame/) | Mengembalikan frame dalam frameset HTML induk untuk target<br/>            hyperlink induk ketika ada.<br/>            Baca/tulis **str**. |
| [`tooltip`](/slides/python-net/id/aspose.slides/ihyperlink/tooltip/) | Mengembalikan string yang mungkin muncul di antarmuka pengguna<br/>            sebagai terkait dengan hyperlink induk.<br/>            Baca/tulis **str**. |
| [`history`](/slides/python-net/id/aspose.slides/ihyperlink/history/) | Menentukan apakah target hyperlink induk akan ditambahkan<br/>            ke dalam daftar hyperlink yang dilihat ketika dipanggil.<br/>            Baca/tulis **bool**. |
| [`highlight_click`](/slides/python-net/id/aspose.slides/ihyperlink/highlight_click/) | Menentukan apakah hyperlink harus disorot saat diklik.<br/>            Baca/tulis **bool**. |
| [`stop_sound_on_click`](/slides/python-net/id/aspose.slides/ihyperlink/stop_sound_on_click/) | Menentukan apakah suara harus dihentikan saat klik hyperlink.<br/>            Baca/tulis **bool**. |
| [`sound`](/slides/python-net/id/aspose.slides/ihyperlink/sound/) | Merepresentasikan suara yang diputar dari hyperlink.<br/>            Baca/tulis [`IAudio`](/slides/python-net/id/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/id/aspose.slides/ihyperlink/color_source/) | Merepresentasikan sumber warna hyperlink - baik gaya maupun format bagian.<br/>            Baca/tulis [`HyperlinkColorSource`](/slides/python-net/id/aspose.slides/hyperlinkcolorsource). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/id/aspose.slides/ihyperlink/equals/#ihyperlink) | Menentukan apakah dua instance Hyperlink sama. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)