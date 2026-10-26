---
title: DeletePictureCroppedAreas()
second_title: Referensi API Aspose.Slides untuk C++
description: Hapus area terpotong dari isi Picture.
type: docs
weight: 430
url: /id/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() metode

Hapus area terpotong dari isi [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### Nilai Kembali

Gambar terpotong atau gambar asli jika pemotongan tidak diperlukan.

## Catatan

Metode ini mengonversi file metafile WMF/EMF menjadi gambar PNG raster sambil memotong.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Menghapus area terpotong dari gambar PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPPImage](../../ippimage/)
* Kelas [PictureFillFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)