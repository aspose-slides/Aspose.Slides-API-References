---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API Referansı
description: Yerleşim slaytına, bir resim, tablo, medya veya metin gibi içeriği tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 1
url: /tr/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metodu


Yerleşim slaytına, bir resim, tablo, medya veya metin gibi içeriği tutmak için yeni bir yer tutucu şekil ekler.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

[IAutoShape](../../iautoshape/) bir İçerik yer tutucusuyla oluşturuldu.
## Açıklamalar



Aşağıdaki örnek, İçerik yer tutucu şeklinin yerleşim slaytına nasıl ekleneceğini gösterir.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ILayoutPlaceholderManager](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)