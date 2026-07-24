---
title: GetImage()
second_title: Aspose.Slides for C++ API Referansı
description: Özel ölçeklendirme ile bir Thumbnail Image nesnesi döndürür.
type: docs
weight: 144
url: /tr/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) yöntemi

Özel ölçeklendirme ile bir Thumbnail Image nesnesi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | **float** | x ekseninde bu Thumbnail'ı ölçeklendirmek için kullanılacak değer. |
| scaleY | **float** | y ekseninde bu Thumbnail'ı ölçeklendirmek için kullanılacak değer. |

### Dönüş Değeri

[IImage](../../iimage/) nesnesi.

## Açıklamalar

Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/)'den küçük resimler nasıl oluşturulacağını gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Aşağıdaki örnek, slaytları bitmap'e dönüştürüp görüntüleri PNG olarak kaydetmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Sunumdaki ilk slaytı bir Bitmap nesnesine dönüştürür
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Görüntüyü PNG formatında kaydeder
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Aşağıdaki örnek, PowerPoint PPT/PPTX dosyalarını JPG'ye dönüştürmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Tam ölçekli bir görsel oluştur
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Görüntüyü JPEG formatında diske kaydet
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Aşağıdaki örnek, PowerPoint PPT/PPTX dosyalarını özelleştirilmiş boyutlarla JPG'ye dönüştürmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Boyutları tanımla
int32_t desiredX = 1200;
int32_t desiredY = 800;
// X ve Y'nin ölçeklendirilmiş değerlerini al
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Tam ölçekli bir görsel oluştur
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Görüntüyü JPEG formatında diske kaydet
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() yöntemi

Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) yöntemi

Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Image nesnesi.

## Açıklamalar

Aşağıdaki örnek, C# kullanarak slaytları özel boyutlarda görüntülere dönüştürmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Sunumdaki ilk slaytı belirtilen boyutta bir Bitmap nesnesine dönüştürür
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Görüntüyü JPEG formatında kaydeder
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) yöntemi

Belirtilen parametrelerle bir Thumbnail tiff görüntü nesnesi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff seçenekleri. |

### Dönüş Değeri

Image nesnesi.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) yöntemi

Bir Thumbnail Image nesnesi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering seçenekleri. |

### Dönüş Değeri

Image nesnesi.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) yöntemi

Özel ölçeklendirme ile bir Thumbnail Image nesnesi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering seçenekleri. |
| scaleX | **float** | x ekseninde bu Thumbnail'ı ölçeklendirmek için kullanılacak değer. |
| scaleY | **float** | y ekseninde bu Thumbnail'ı ölçeklendirmek için kullanılacak değer. |

### Dönüş Değeri

Bitmap nesneleri.

## Açıklamalar

Aşağıdaki örnek, C# kullanarak notlar ve yorumlarla slaytları [Images](../../images/)'ye dönüştürmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Renderleme seçeneklerini oluştur
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Notlar ve yorumlar için yerleşim seçeneklerini oluştur
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Sayfadaki notların konumunu ayarlar
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Sayfadaki yorumların konumunu ayarlar
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Yorum çıkış alanının genişliğini ayarlar
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Yorum alanının rengini ayarlar
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Renderleme için yerleşim seçeneklerini ayarla
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Sunumdaki ilk slaytı bir IImage nesnesine dönüştürür
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Görüntüyü GIF formatında kaydeder
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) yöntemi

Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering seçenekleri. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Image nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)