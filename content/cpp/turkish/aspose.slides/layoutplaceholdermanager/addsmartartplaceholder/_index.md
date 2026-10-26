---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir yer tutucu şekli ekler layout slaytına SmartArt diyagramını tutmak için.
type: docs
weight: 92
url: /tr/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) metot

Yeni bir yer tutucu şekli ekler layout slaytına [SmartArt](../../../aspose.slides.smartart/) diyagramını tutmak için.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

Oluşturulan [IAutoShape](../../iautoshape/) bir [SmartArt](../../../aspose.slides.smartart/) yer tutucu ile.

## Açıklamalar

Aşağıdaki örnek, [SmartArt](../../../aspose.slides.smartart/) yer tutucu şeklinin layout slaytına nasıl ekleneceğini gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [LayoutPlaceholderManager](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)