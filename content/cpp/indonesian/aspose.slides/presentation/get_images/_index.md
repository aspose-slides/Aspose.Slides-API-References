---
title: get_Images()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi semua gambar dalam presentasi. Hanya-baca IImageCollection.
type: docs
weight: 209
url: /id/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() metode


Mengembalikan koleksi semua gambar dalam presentasi. Hanya-baca [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Catatan


Contoh berikut menunjukkan cara menambahkan gambar sebagai BLOB di PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// membuat presentasi baru yang akan ditambahkan gambar.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Mari tambahkan gambar ke presentasi - kami memilih perilaku KeepLocked karena kami
// TIDAK bermaksud mengakses file "largeImage.png".
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Menyimpan presentasi. Saat presentasi besar dihasilkan, konsumsi memori
// tetap rendah selama siklus hidup objek pres
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Contoh berikut menambahkan hyperlink ke gambar di PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Menambahkan gambar ke presentasi
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Membuat bingkai gambar pada slide 1 berdasarkan gambar yang telah ditambahkan sebelumnya
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImageCollection](../../iimagecollection/)
* Kelas [Presentation](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)