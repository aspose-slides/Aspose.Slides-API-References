---
title: AddTextPlaceholder()
second_title: Aspose.Slides for C++ API Referansı
description: Düzen slaytına metin içeriği tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 27
url: /tr/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metot

Düzen slaytına metin içeriği tutmak için yeni bir yer tutucu şekil ekler.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

Bir Text yer tutucusu ile [IAutoShape](../../iautoshape/) oluşturuldu.
## Açıklamalar

Aşağıdaki örnek, Text yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [LayoutPlaceholderManager](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)