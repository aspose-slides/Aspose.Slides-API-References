---
title: DeletePictureCroppedAreas()
second_title: Referensi API Aspose.Slides untuk C++
description: Hapus area yang dipotong dari pengisian Gambar.
type: docs
weight: 430
url: /id/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() metode

Hapus area yang dipotong dari pengisian [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### Nilai Kembali

Gambar yang dipotong atau gambar asli jika pemotongan tidak diperlukan.
## Catatan

Metode ini mengonversi metafile WMF/EMF menjadi gambar raster PNG sambil memotong.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Mendapatkan PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Menghapus area yang dipotong dari gambar PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)