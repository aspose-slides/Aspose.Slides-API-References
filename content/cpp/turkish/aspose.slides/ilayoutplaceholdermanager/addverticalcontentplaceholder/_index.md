---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides for C++ API Referansı
description: Dikey yönde bir resim, tablo, medya veya metin gibi içeriği tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 14
url: /tr/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) metodu

Yeni içerik (örneğin resim, tablo, medya veya metin) tutmak üzere düzen slaytına dikey yönde yeni bir yer tutucu şekil ekler.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

İçerik (Dikey) yer tutucu ile oluşturulan [IAutoShape](../../iautoshape/).

## Açıklamalar

Aşağıdaki örnek, İçerik (Dikey) yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ILayoutPlaceholderManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)