---
title: IParagraphFormat
second_title: Aspose.Sildes untuk Referensi API .NET
description: Kelas ini berisi properti pemformatan paragraf. Tidak seperti IParagraphFormatEffectiveData./iparagraphformateffectivedata semua properti dari kelas ini dapat ditulis.
type: docs
weight: 6590
url: /id/aspose.slides/iparagraphformat/
---
## IParagraphFormat antarmuka

Kelas ini berisi properti pemformatan paragraf. Tidak seperti [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), semua properti dari kelas ini dapat ditulis.

```csharp
public interface IParagraphFormat
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. Baca/tulis [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Mengembalikan format bullet paragraf. Hanya-baca [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Mengembalikan format bagian default sebuah paragraf. Tidak ada pewarisan yang diterapkan. Hanya-baca [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. Baca/tulis Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Mengembalikan atau mengatur kedalaman paragraf. Nilai 0 berarti nilai tidak terdefinisi. Baca/tulis Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Menentukan apakah jeda baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. Baca/tulis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Mengembalikan atau mengatur Indent Baris Pertama/Indent Gantung paragraf tanpa pewarisan. Indent Gantung dapat didefinisikan dengan nilai negatif. Baca/tulis Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Menentukan apakah jeda baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. Baca/tulis Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. Baca/tulis Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Menentukan apakah penulisan Dari Kanan ke Kiri digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Mengembalikan atau mengatur jumlah ruang antara baris dasar dalam paragraf. Nilai positif berarti persentase, negatif berarti ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Baca/tulis Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Mengembalikan tabulasi paragraf. Tidak ada pewarisan yang diterapkan. Hanya-baca [`ITabCollection`](../itabcollection). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Mendapatkan data pemformatan paragraf efektif dengan pewarisan yang diterapkan. |

### Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam kebanyakan kasus Anda akan mendapatkan nilai yang berarti "tidak terdefinisi".

Untuk mendapatkan nilai parameter pemformatan efektif termasuk yang diwarisi, Anda perlu menggunakan metode [`GetEffective`](./geteffective) yang mengembalikan sebuah instance [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Lihat Juga

* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->