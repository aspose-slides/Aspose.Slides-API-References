---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API Referansı
description: Dolgu Picture'ın kırpılmış alanlarını sil.
type: docs
weight: 430
url: /tr/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() yöntem


Dolgunun kırpılmış alanlarını sil [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### Dönüş Değeri

Kırpılmış görüntü veya kırpma gerekli değilse orijinal görüntü.
## Açıklamalar


Bu yöntem, kırpma sırasında WMF/EMF metafilelerini raster PNG görüntüsüne dönüştürür.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame'i alır
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame resminin kırpılmış alanlarını siler
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [IPictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)