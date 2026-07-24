---
title: AddTextPlaceholder()
second_title: Aspose.Slides için C++ API Referansı
description: Düzen slaytına metin içeriği tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 27
url: /tr/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metodu

Düzen slaytına metin içeriği tutmak için yeni bir yer tutucu şekil ekler.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

[IAutoShape](../../iautoshape/) bir Metin yer tutucu ile oluşturuldu.

## Açıklamalar

Aşağıdaki örnek, Metin yer tutucu şeklini düzen slaytına nasıl ekleyeceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ILayoutPlaceholderManager](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)