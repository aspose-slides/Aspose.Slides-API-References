---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API Referansı
description: Dolgu Picture'ın kırpılmış alanlarını sil.
type: docs
weight: 430
url: /tr/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() metot

Dolgu [Picture](../../picture/)'nin kırpılmış alanlarını sil.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### Dönüş Değeri

Kırpılmış görüntü veya kırpma gerekli değilse orijinal görüntü.

## Açıklamalar

Bu metot, WMF/EMF metafile'larını kırparak raster PNG görüntüsüne dönüştürür.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame'i alır
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame görüntüsünün kırpılmış alanlarını siler
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Başvurular

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [PictureFillFormat](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)