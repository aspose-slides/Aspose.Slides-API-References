---
title: CompressImage()
second_title: Aspose.Slides for C++ API Referansı
description: Şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek görüntüyü sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler.
type: docs
weight: 443
url: /tr/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) yöntemi

Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true ise, yöntem görüntünün kırpılmış alanlarını kaldıracak, böylece boyutunu daha da azaltabilir. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Sıkıştırma için hedef çözünürlük, [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) enum değerine göre belirtilir. |

### Dönüş Değeri

Görüntünün başarıyla sıkıştırılıp sıkıştırılmadığını gösteren bir **bool**. Döndürür ****true****

## Açıklamalar

Bu yöntem, PowerPoint'in "Picture Format -> Compress Pictures" özelliğine benzer şekilde görüntünün boyutunu ve çözünürlüğünü değiştirir.

görüntü yeniden boyutlandırıldıysa veya kırpıldıysa, aksi takdirde ****false****

.

Aşağıdaki örnek, hedef çözünürlüğü ayarlayarak ve kırpılmış alanları kaldırarak bir sunumdaki görüntünün boyutunu küçültmek için **CompressImage** yönteminin nasıl kullanılacağını gösterir:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Görüntüyü hedef çözünürlük 150 DPI (Web çözünürlüğü) ile sıkıştır ve kırpılmış alanları kaldır
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) yöntemi

Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true ise, yöntem görüntünün kırpılmış alanlarını kaldıracak, böylece boyutunu daha da azaltabilir. |
| resolution | **float** | DPI cinsinden hedef çözünürlük. Bu değer pozitif olmalı ve görüntünün nasıl yeniden boyutlandırılacağını tanımlar. |

### Dönüş Değeri

Görüntünün başarıyla sıkıştırılıp sıkıştırılmadığını gösteren bir **bool**. Döndürür ****true****

## Açıklamalar

Bu yöntem, PowerPoint'in "Picture Format -> Compress Pictures" özelliğine benzer şekilde görüntünün boyutunu ve çözünürlüğünü değiştirir.

görüntü yeniden boyutlandırıldıysa veya kırpıldıysa, aksi takdirde ****false****

.

Aşağıdaki örnek, hedef çözünürlüğü ayarlayarak ve kırpılmış alanları kaldırarak bir sunumdaki görüntünün boyutunu küçültmek için **CompressImage** yönteminin nasıl kullanılacağını gösterir:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame'i alır
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Görüntüyü hedef çözünürlük 150 DPI (Web çözünürlüğü) ile sıkıştır ve kırpılmış alanları kaldır
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web çözünürlüğü
```

## İlgili

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)