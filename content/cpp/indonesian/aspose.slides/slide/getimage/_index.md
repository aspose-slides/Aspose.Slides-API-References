---
title: GetImage()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek Thumbnail Image dengan skala khusus.
type: docs
weight: 144
url: /id/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) metode

Mengembalikan objek Thumbnail Image dengan skala khusus.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

[IImage](../../iimage/) objek.

## Catatan

Contoh berikut menunjukkan cara menghasilkan thumbnail dari PowerPoint [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Contoh berikut menunjukkan cara mengonversi slide menjadi bitmap dan menyimpan gambar dalam format PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Mengkonversi slide pertama dalam presentasi menjadi objek Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Menyimpan gambar dalam format PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Contoh berikut menunjukkan cara mengonversi PowerPoint PPT/PPTX menjadi JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Membuat gambar skala penuh
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Simpan gambar ke disk dalam format JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Contoh berikut menunjukkan cara mengonversi PowerPoint PPT/PPTX menjadi JPG dengan dimensi yang disesuaikan: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Tentukan dimensi
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Dapatkan nilai skala X dan Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Buat gambar skala penuh
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Simpan gambar ke disk dalam format JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() metode

Mengembalikan objek Thumbnail Image (20% dari ukuran sebenarnya).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) metode

Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

Objek Image.

## Catatan

Contoh berikut menunjukkan cara mengonversi slide menjadi gambar dengan ukuran khusus menggunakan C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Mengonversi slide pertama dalam presentasi menjadi Bitmap dengan ukuran yang ditentukan
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Menyimpan gambar dalam format JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metode

Mengembalikan objek gambar tiff Thumbnail dengan parameter yang ditentukan.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opsi tiff. |

### Nilai Kembali

Objek Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metode

Mengembalikan objek Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |

### Nilai Kembali

Objek Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metode

Mengembalikan objek Thumbnail Image dengan skala khusus.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| scaleX | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

Objek Bitmap.

## Catatan

Contoh berikut menunjukkan cara mengonversi slide dengan catatan dan komentar menjadi [Images](../../images/) menggunakan C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Buat opsi rendering
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Buat opsi tata letak catatan dan komentar
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Menetapkan posisi catatan pada halaman
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Menetapkan posisi komentar pada halaman
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Menetapkan lebar area keluaran komentar
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Menetapkan warna untuk area komentar
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Atur opsi tata letak untuk rendering
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Mengonversi slide pertama presentasi menjadi objek IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Menyimpan gambar dalam format GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metode

Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

Objek Image.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)