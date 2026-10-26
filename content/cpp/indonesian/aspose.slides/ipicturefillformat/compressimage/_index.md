---
title: CompressImage()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.
type: docs
weight: 443
url: /id/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) metode


Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jika true, metode akan menghapus area yang dipotong dari gambar, yang berpotensi lebih mengurangi ukurannya. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Resolusi target untuk kompresi, ditentukan sebagai nilai enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Nilai Kembali

Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompresi. Mengembalikan ****true****

## Keterangan


Metode ini mengubah ukuran dan resolusi gambar serupa dengan fitur PowerPoint "Picture Format -> Compress Pictures".


jika gambar diubah ukurannya atau dipotong, bila tidak ****false****

. 


Contoh berikut menunjukkan cara menggunakan metode **CompressImage** untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area yang dipotong: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Kompres gambar dengan resolusi target 150 DPI (resolusi Web) dan hapus area yang dipotong
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) metode


Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jika true, metode akan menghapus area yang dipotong dari gambar, yang berpotensi lebih mengurangi ukurannya. |
| resolution | **float** | Resolusi target dalam DPI. Nilai ini harus positif dan menentukan bagaimana gambar akan diubah ukurannya. |

### Nilai Kembali

Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompresi. Mengembalikan ****true****

## Keterangan


Metode ini mengubah ukuran dan resolusi gambar serupa dengan fitur PowerPoint "Picture Format -> Compress Pictures".


jika gambar diubah ukurannya atau dipotong, bila tidak ****false****

. 


Contoh berikut menunjukkan cara menggunakan metode **CompressImage** untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area yang dipotong: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Kompres gambar dengan resolusi target 150 DPI (resolusi Web) dan hapus area yang dipotong
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // resolusi Web
```

## Lihat Juga

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Kelas [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)