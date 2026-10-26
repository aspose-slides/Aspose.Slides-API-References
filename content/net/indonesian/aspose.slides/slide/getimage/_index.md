---
title: GetImage
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengembalikan objek Thumbnail Image dengan skala khusus.
type: docs
weight: 80
url: /id/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Mengembalikan objek Thumbnail Image dengan skala khusus.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | Single | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | Single | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

objek IImage.

### Contoh

Contoh berikut menunjukkan cara menghasilkan thumbnail dari Presentasi PowerPoint.

```csharp
[C#]
// Membuat instansi kelas Presentation yang mewakili file presentasi
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Mengakses slide pertama
    ISlide sld = pres.Slides[0];
    // Membuat gambar dengan skala penuh
    IImage bmp = sld.GetImage(1f, 1f);
    // Menyimpan gambar ke disk dalam format JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Contoh berikut menunjukkan cara mengonversi slide menjadi bitmap dan menyimpan gambar dalam format PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Mengonversi slide pertama dalam presentasi menjadi objek Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Menyimpan gambar dalam format PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint PPT/PPTX ke JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Membuat gambar dengan skala penuh
		IImage bmp = sld.GetImage(1f, 1f);
		// Menyimpan gambar ke disk dalam format JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint PPT/PPTX ke JPG dengan dimensi yang disesuaikan.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Mendefinisikan dimensi
	int desiredX = 1200;
	int desiredY = 800;
	// Mendapatkan nilai skala X dan Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Membuat gambar dengan skala penuh
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Menyimpan gambar ke disk dalam format JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Lihat Juga

* antarmuka [IImage](../../iimage)
* kelas [Slide](../../slide)
* ruang nama [Aspose.Slides](../../slide)
* rakitan [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Mengembalikan objek Thumbnail Image (20% dari ukuran sebenarnya).

```csharp
public IImage GetImage()
```

### Lihat Juga

* antarmuka [IImage](../../iimage)
* kelas [Slide](../../slide)
* ruang nama [Aspose.Slides](../../slide)
* rakitan [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan.

```csharp
public IImage GetImage(Size imageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSize | Size | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

objek Image.

### Contoh

Contoh berikut menunjukkan cara mengonversi slide menjadi gambar dengan ukuran khusus menggunakan C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Mengonversi slide pertama dalam presentasi menjadi Bitmap dengan ukuran yang ditentukan
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Menyimpan gambar dalam format JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Lihat Juga

* antarmuka [IImage](../../iimage)
* kelas [Slide](../../slide)
* ruang nama [Aspose.Slides](../../slide)
* rakitan [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Mengembalikan objek gambar tiff Thumbnail dengan parameter yang ditentukan.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | ITiffOptions | Opsi Tiff. |

### Nilai Kembali

objek Image.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| InvalidOperationException | Dilempar ketika options.SlideLayoutOption adalah NotesCommentsLayoutingOptions dan propertinya NotesPosition mengambil nilai NotesPositions.BottomFull. |

### Lihat Juga

* antarmuka [IImage](../../iimage)
* antarmuka [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* kelas [Slide](../../slide)
* ruang nama [Aspose.Slides](../../slide)
* rakitan [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Mengembalikan objek Thumbnail Image.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | IRenderingOptions | Opsi rendering. |

### Nilai Kembali

objek Image.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| InvalidOperationException | Dilempar ketika notesCommentsLayouting.NotesPosition mengambil nilai NotesPositions.BottomFull. |

### Lihat Juga

* antarmuka [IImage](../../iimage)
* antarmuka [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* kelas [Slide](../../slide)
* ruang nama [Aspose.Slides](../../slide)
* rakitan [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Mengembalikan objek Thumbnail Image dengan skala khusus.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | IRenderingOptions | Opsi rendering. |
| scaleX | Single | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | Single | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

objek Bitmap.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| InvalidOperationException | Dilempar ketika notesCommentsLayouting.NotesPosition mengambil nilai NotesPositions.BottomFull. |

### Contoh

Contoh berikut menunjukkan cara mengonversi slide dengan catatan dan komentar menjadi Gambar menggunakan C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Membuat opsi rendering
    IRenderingOptions options = new RenderingOptions();
    // Membuat opsi tata letak catatan dan komentar
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Menetapkan posisi catatan pada halaman
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Menetapkan posisi komentar pada halaman
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Menetapkan lebar area output komentar
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Menetapkan warna untuk area komentar
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Menetapkan opsi tata letak untuk rendering
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Mengonversi slide pertama dari presentasi menjadi objek IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Menyimpan gambar dalam format GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Lihat Juga

* antarmuka [IImage](../../iimage)
* antarmuka [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* kelas [Slide](../../slide)
* ruang nama [Aspose.Slides](../../slide)
* rakitan [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | IRenderingOptions | Opsi rendering. |
| imageSize | Size | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

objek Image.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| InvalidOperationException | Dilempar ketika options.SlideLayoutOption adalah NotesCommentsLayoutingOptions dan propertinya NotesPosition mengambil nilai NotesPositions.BottomFull. |

### Lihat Juga

* antarmuka [IImage](../../iimage)
* antarmuka [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* kelas [Slide](../../slide)
* ruang nama [Aspose.Slides](../../slide)
* rakitan [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->