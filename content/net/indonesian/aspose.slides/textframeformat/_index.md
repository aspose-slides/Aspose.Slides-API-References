---
title: TextFrameFormat
second_title: Referensi API Aspose.Sildes untuk .NET
description: Berisi properti formatTextFrameFormatting milik TextFrames.
type: docs
weight: 10980
url: /id/aspose.slides/textframeformat/
---
## TextFrameFormat kelas

Berisi properti formatTextFrameFormatting milik TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Menginisialisasi instance baru dari kelas [`TextFrameFormat`](../textframeformat). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. Baca/tulis [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Memungkinkan untuk mendapatkan antarmuka IPresentationComponent dasar. Hanya-baca [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Mengembalikan atau mengatur mode autofit teks. Baca/tulis [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Jika NullableBool.True maka teks harus dipusatkan secara horizontal dalam kotak. Baca/tulis [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Mengembalikan atau mengatur jumlah kolom dalam area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur ke nol. Nilai 0 berarti nilai tidak terdefinisi. Baca/tulis Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Mengembalikan atau mengatur spasi antar kolom teks dalam area teks (dalam poin). Ini hanya berlaku ketika ada lebih dari 1 kolom. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur ke nol. Baca/tulis Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Mengambil atau mengatur agar teks tetap datar meskipun efek Rotasi 3-D diterapkan. Baca/tulis Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Mengembalikan atau mengatur margin bawah (poin) dalam TextFrame. Baca/tulis Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Mengembalikan atau mengatur margin kiri (poin) dalam TextFrame. Baca/tulis Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Mengembalikan atau mengatur margin kanan (poin) dalam TextFrame. Baca/tulis Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Mengembalikan atau mengatur margin atas (poin) dalam TextFrame. Baca/tulis Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Menentukan rotasi kustom yang diterapkan pada teks dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang menyertainya digunakan. Jika ditentukan, maka ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi yang diterapkan selain rotasi pada teks itu sendiri. Nilai rotasi visual teks yang dihasilkan merupakan rangkuman dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Baca/tulis Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Menentukan orientasi teks. Nilai rotasi visual teks yang dihasilkan merupakan rangkuman dari properti ini dan sudut kustom dalam properti RotationAngle. Baca/tulis [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang mewakili properti efek 3d untuk teks. Hanya-baca [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Mengambil atau mengatur bentuk pelipatan teks. Baca/tulis [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** jika teks dilipat pada margin TextFrame. Baca/tulis [`NullableBool`](../nullablebool). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Membandingkan dengan objek yang ditentukan. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Mengambil data format bingkai teks yang efektif dengan pewarisan yang diterapkan. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Mengembalikan kode hash. |

### Lihat Juga

* kelas [PVIObject](../pviobject)
* antarmuka [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* antarmuka [ITextFrameFormat](../itextframeformat)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->