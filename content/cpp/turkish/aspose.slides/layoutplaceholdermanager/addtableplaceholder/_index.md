---
title: AddTablePlaceholder()
second_title: C++ için Aspose.Slides API Referansı
description: Bir tablo tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.
type: docs
weight: 79
url: /tr/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) metod

Yeni bir tablo tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

Oluşturulan [IAutoShape](../../iautoshape/) bir [Table](../../table/) yer tutucu ile.

## Açıklamalar

Aşağıdaki örnek, [Table](../../table/) yer tutucu şeklini düzen slaytına nasıl ekleyeceğinizi gösterir.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)