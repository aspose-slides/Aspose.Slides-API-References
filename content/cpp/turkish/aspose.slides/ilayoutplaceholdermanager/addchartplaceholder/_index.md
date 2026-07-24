---
title: AddChartPlaceholder()
second_title: Aspose.Slides for C++ API Referansı
description: Düzen slaytına bir grafik tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 66
url: /tr/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) yöntemi

Düzen slaytına bir Chart tutmak için yeni bir yer tutucu şekli ekler.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

Bir Chart yer tutucusuyla [IAutoShape](../../iautoshape/) oluşturuldu.
## Açıklamalar

Aşağıdaki örnek, Chart yer tutucu şeklini düzen slaytına nasıl ekleyeceğinizi gösterir.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Diğer bölümler

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ILayoutPlaceholderManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)