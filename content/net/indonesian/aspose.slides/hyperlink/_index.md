---
title: Hyperlink
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili sebuah hyperlink.
type: docs
weight: 5120
url: /id/aspose.slides/hyperlink/
---
## Hyperlink kelas

Mewakili sebuah hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Membuat sebuah instance hyperlink yang mengarah ke slide tertentu. Catatan: hyperlink yang dibuat harus ditetapkan ke objek lain dari presentasi yang sama, jika tidak tautan akan disimpan sebagai NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Membuat sebuah instance hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Membuat sebuah instance hyperlink menggunakan hyperlink lain sebagai sumber, menggantikan properti sekunder. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Mengembalikan hyperlink yang mengakhiri pertunjukan. Hanya baca [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Mengembalikan hyperlink ke slide pertama presentasi. Hanya baca [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Mengembalikan hyperlink ke slide terakhir presentasi. Hanya baca [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Mengembalikan hyperlink ke slide terakhir yang dilihat. Hanya baca [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Mengembalikan hyperlink khusus "play mediafile". Digunakan dalam AudioFrame dan VideoFrame. Hanya baca [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Mengembalikan hyperlink ke slide berikutnya. Hanya baca [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Mengembalikan hyperlink khusus "do nothing". Hanya baca [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Mengembalikan hyperlink ke slide sebelumnya. Hanya baca [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Mengembalikan tipe aksi Hyperlink. Hanya baca [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Memungkinkan mendapatkan antarmuka dasar IPresentationComponent. Hanya baca [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Mewakili sumber warna hyperlink - baik gaya atau format bagian. Baca/tulis [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Menentukan URL eksternal. Hanya baca String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Mewakili sebuah hyperlink yang ditetapkan untuk bagian ini tanpa memperhatikan konten sebenarnya dari bagian tersebut. PowerPoint memperlakukan tautan dan teks yang bersesuaian dalam sebuah bagian secara khusus. Ini memungkinkan membuat teks untuk hyperlink dalam bentuk URL yang valid, berbeda dari alamat sebenarnya dari tautan. Dalam kasus ini, ketika Anda melihat tautan di jendela penyuntingan, tautan tersebut akan diubah agar sesuai dengan bagian teks. Properti ini mewakili nilai asli hyperlink. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Menentukan apakah hyperlink harus disorot saat diklik. Baca/tulis Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Menentukan apakah target hyperlink induk akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. Baca/tulis Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Mewakili suara yang diputar oleh hyperlink. Baca/tulis [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Menentukan apakah suara harus dihentikan saat hyperlink diklik. Baca/tulis Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk ketika ada. Baca/tulis String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Jika Hyperlink menargetkan slide tertentu, mengembalikan slide tersebut. Hanya baca [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. Baca/tulis String. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Menentukan apakah dua instance Hyperlink sama. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Menentukan apakah dua instance Hyperlink sama. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Menguji dua hyperlink untuk kesamaan. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Menguji dua hyperlink untuk ketidaksamaan. |

### Lihat Juga

* kelas [PVIObject](../pviobject)
* antarmuka [IHyperlink](../ihyperlink)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->