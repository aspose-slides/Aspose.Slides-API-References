---
title: ParagraphFormat
second_title: Referensi API Aspose.Sildes untuk .NET
description: Kelas ini berisi properti pemformatan paragraf. Tidak seperti IParagraphFormatEffectiveData./iparagraphformateffectivedata semua properti dari kelas ini dapat ditulis.
type: docs
weight: 9310
url: /id/aspose.slides/paragraphformat/
---
## ParagraphFormat kelas

Kelas ini berisi properti pemformatan paragraf. Tidak seperti [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), semua properti dari kelas ini dapat ditulis.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Menginisialisasi sebuah instance baru dari kelas [`ParagraphFormat`](../paragraphformat). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. Baca/tulis [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Mengizinkan mengambil antarmuka dasar IPresentationComponent. Baca-saja [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. Baca/tulis Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Menentukan apakah pemenggalan baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. Baca/tulis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Menentukan apakah tanda baca menggantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Mengembalikan atau mengatur Indent Baris Pertama/Indent Gantung paragraf tanpa pewarisan. Indent Gantung dapat didefinisikan dengan nilai negatif. Baca/tulis Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Menentukan apakah pemenggalan baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. Baca/tulis Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. Baca/tulis Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Menentukan apakah penulisan Dari Kanan ke Kiri digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, negatif berarti ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Baca/tulis Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Mengembalikan tabulasi paragraf. Tidak ada pewarisan yang diterapkan. Baca-saja [`ITabCollection`](../itabcollection). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Membandingkan dengan objek yang ditentukan. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan diterapkan. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Mengembalikan kode hash. |

### Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam sebagian besar kasus Anda akan mendapatkan nilai yang berarti "tidak terdefinisi".

Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwariskan, Anda perlu menggunakan metode [`GetEffective`](./geteffective) yang mengembalikan sebuah instance [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Lihat Juga

* kelas [PVIObject](../pviobject)
* antarmuka [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* antarmuka [IParagraphFormat](../iparagraphformat)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->