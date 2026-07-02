---
title: IPictureFillFormat
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili gaya isian gambar.
type: docs
weight: 6630
url: /id/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat antarmuka

Mewakili gaya isian gambar.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Mengizinkan untuk mendapatkan antarmuka IFillParamSource dasar. Hanya-baca [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Mengembalikan atau mengatur jumlah persentase tinggi gambar asli yang dipotong dari bagian bawah gambar. Baca/tulis Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Mengembalikan atau mengatur jumlah persentase lebar gambar asli yang dipotong dari sisi kiri gambar. Baca/tulis Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Mengembalikan atau mengatur jumlah persentase lebar gambar asli yang dipotong dari sisi kanan gambar. Baca/tulis Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Mengembalikan atau mengatur jumlah persentase tinggi gambar asli yang dipotong dari bagian atas gambar. Baca/tulis Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Mengembalikan atau mengatur DPI yang digunakan untuk mengisi gambar. Baca/tulis Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Mengembalikan gambar. Hanya-baca [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Mengembalikan atau mengatur mode isian gambar. Baca/tulis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Mengembalikan atau mengatur tepi bawah persegi isi yang didefinisikan oleh offset persentase dari tepi bawah kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sedangkan persentase negatif menunjukkan penonjolan. Baca/tulis Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Mengembalikan atau mengatur tepi kiri persegi isi yang didefinisikan oleh offset persentase dari tepi kiri kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sedangkan persentase negatif menunjukkan penonjolan. Baca/tulis Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Mengembalikan atau mengatur tepi kanan persegi isi yang didefinisikan oleh offset persentase dari tepi kanan kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sedangkan persentase negatif menunjukkan penonjolan. Baca/tulis Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Mengembalikan atau mengatur tepi atas persegi isi yang didefinisikan oleh offset persentase dari tepi atas kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sedangkan persentase negatif menunjukkan penonjolan. Baca/tulis Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Mengembalikan atau mengatur cara tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana pola tersebut diulang di seluruh bentuk. Baca/tulis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Membalikkan ubin tekstur secara horizontal, vertikal, atau kedua sumbu. Baca/tulis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Mengembalikan atau mengatur offset horizontal tekstur dari asal bentuk dalam poin. Nilai positif menggeser tekstur ke kanan, sedangkan nilai negatif menggeser ke kiri. Baca/tulis Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Mengembalikan atau mengatur offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif menggeser tekstur ke bawah, sedangkan nilai negatif menggeser ke atas. Baca/tulis Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Mengembalikan atau mengatur skala horizontal untuk isian tekstur sebagai persentase. Baca/tulis Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Mengembalikan atau mengatur skala vertikal untuk isian tekstur sebagai persentase. Baca/tulis Single. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Menghapus area yang dipotong dari Gambar isian. |

### Lihat Juga

* antarmuka [IFillParamSource](../ifillparamsource)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->