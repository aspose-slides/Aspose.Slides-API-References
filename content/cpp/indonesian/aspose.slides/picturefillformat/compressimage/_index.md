---
title: CompressImage()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.
type: docs
weight: 443
url: /id/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) metode

Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jika true, metode ini akan menghapus area yang dipotong dari gambar, berpotensi lebih lanjut mengurangi ukurannya. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Resolusi target untuk kompresi, ditentukan sebagai nilai dari enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Nilai Kembalian

Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompres. Mengembalikan ****true****

## Catatan

Metode ini mengubah ukuran dan resolusi gambar serupa dengan fitur "Picture Format -> Compress Pictures" pada PowerPoint.

jika gambar diubah ukurannya atau dipotong, jika tidak ****false****

.

Contoh berikut menunjukkan cara menggunakan metode **CompressImage** untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area yang dipotong:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Kompres gambar dengan resolusi target 150 DPI (resolusi Web) dan hapus area yang dipotong
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) metode

Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jika true, metode ini akan menghapus area yang dipotong dari gambar, berpotensi lebih lanjut mengurangi ukurannya. |
| resolution | **float** | Resolusi target dalam DPI. Nilai ini harus positif dan menentukan bagaimana gambar akan diubah ukurannya. |

### Nilai Kembalian

Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompres. Mengembalikan ****true****

## Catatan

Metode ini mengubah ukuran dan resolusi gambar serupa dengan fitur "Picture Format -> Compress Pictures" pada PowerPoint.

jika gambar diubah ukurannya atau dipotong, jika tidak ****false****

.

Contoh berikut menunjukkan cara menggunakan metode **CompressImage** untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area yang dipotong:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Kompres gambar dengan resolusi target 150 DPI (resolusi Web) dan hapus area yang dipotong
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Resolusi Web
```

## Lihat Juga

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Kelas [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)