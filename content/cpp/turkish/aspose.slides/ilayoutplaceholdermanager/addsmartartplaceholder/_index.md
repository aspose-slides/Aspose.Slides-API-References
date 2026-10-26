---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir yer tutucu şekil ekler ve bu şekil bir SmartArt diyagramını tutar.
type: docs
weight: 92
url: /tr/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) method

Düzen slaytına yeni bir yer tutucu şekil ekler ve bu şekil bir [SmartArt](../../../aspose.slides.smartart/) diyagramını tutar.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

[IAutoShape](../../iautoshape/) bir [SmartArt](../../../aspose.slides.smartart/) yer tutucusuyla oluşturuldu.

## Açıklamalar

Aşağıdaki örnek, [SmartArt](../../../aspose.slides.smartart/) yer tutucu şeklini düzen slaytına nasıl ekleyeceğinizi gösterir.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)