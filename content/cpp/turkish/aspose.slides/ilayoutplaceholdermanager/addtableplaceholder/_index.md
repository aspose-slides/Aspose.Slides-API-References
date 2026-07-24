---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ API Referansı
description: Düzen slaytına bir tablo tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 79
url: /tr/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) metodu

Düzen slaytına bir tablo tutmak için yeni bir yer tutucu şekil ekler.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

Oluşturuldu [IAutoShape](../../iautoshape/) bir [Table](../../table/) yer tutucu.

## Açıklamalar

Aşağıdaki örnek, [Table](../../table/) yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Ayrıca Bakınız

* TipTanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ILayoutPlaceholderManager](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)