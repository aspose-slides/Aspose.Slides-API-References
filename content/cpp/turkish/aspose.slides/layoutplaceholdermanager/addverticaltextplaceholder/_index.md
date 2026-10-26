---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides için C++ API Referansı
description: Dikey yönde metin içeriğini tutmak için yerleşim slaytına yeni bir yer tutucu şekli ekler.
type: docs
weight: 40
url: /tr/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) method

Dikey yönde metin içeriğini tutmak için yerleşim slaytına yeni bir yer tutucu şekli ekler.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

Metin (Vertical) yer tutucu ile [IAutoShape](../../iautoshape/) oluşturuldu.

## Açıklamalar

Aşağıdaki örnek, Text (Vertical) yer tutucu şeklinin yerleşim slaytına nasıl ekleneceğini gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)