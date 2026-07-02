---
title: ParagraphFormat
second_title: Aspose.Sildes untuk Referensi API .NET
description: Kelas ini berisi properti pemformatan paragraf. Berbeda dengan IParagraphFormatEffectiveData./iparagraphformateffectivedata semua properti dari kelas ini dapat ditulis.
type: docs
weight: 9290
url: /id/aspose.slides/paragraphformat/
---
## ParagraphFormat kelas

Kelas ini berisi properti pemformatan paragraf. Berbeda dengan [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), semua properti dari kelas ini dapat ditulis.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Menginisialisasi instance baru dari [`ParagraphFormat`](../paragraphformat) kelas. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. Baca/tulis [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Memungkinkan untuk mendapatkan antarmuka IPresentationComponent dasar. Baca-saja [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. Baca/tulis Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Menentukan apakah pemutus baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. Baca/tulis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Mengembalikan atau mengatur Inden Baris Pertama/Inden Gantung paragraf tanpa pewarisan. Inden Gantung dapat didefinisikan dengan nilai negatif. Baca/tulis Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Menentukan apakah pemutus baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. Baca/tulis Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. Baca/tulis Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Menentukan apakah penulisan kanan-ke-kiri digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam ukuran poin. Baca/tulis Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam ukuran poin. Baca/tulis Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, negatif berarti ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Baca/tulis Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Mengembalikan tabulasi paragraf. Tidak ada pewarisan yang diterapkan. Baca-saja [`ITabCollection`](../itabcollection). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Membandingkan dengan objek yang ditentukan. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Mendapatkan data pemformatan paragraf efektif dengan pewarisan diterapkan. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Mengembalikan kode hash. |

### Keterangan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti bahwa tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam sebagian besar kasus Anda akan mendapatkan nilai yang berarti "undefined".

Untuk memperoleh nilai parameter pemformatan efektif termasuk yang diwariskan, Anda perlu menggunakan metode [`GetEffective`](./geteffective) yang mengembalikan sebuah instance [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Lihat Juga

* kelas [PVIObject](../pviobject)
* antarmuka [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* antarmuka [IParagraphFormat](../iparagraphformat)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->