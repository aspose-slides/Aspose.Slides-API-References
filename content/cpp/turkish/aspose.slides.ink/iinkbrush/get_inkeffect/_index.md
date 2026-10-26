---
title: get_InkEffect()
second_title: Aspose.Slides için C++ API Referansı
description: "Kalem darbesinin görsel stilini tanımlayan mürekkep efekti tipini alır (örn., Galaxy, Gold, Silver). Değer, fırça özelliği \"inkEffects\" üzerinden ayrıştırılır. Tanınan bir efekt belirtilmezse, InkEffectType::NotDefined döndürülür."
type: docs
weight: 53
url: /tr/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() metodu

Kalem darbesinin görsel stilini tanımlayan mürekkep efekti türünü (ör. Galaxy, Gold, Silver) alır. Değer, fırça özelliği \"inkEffects\" içinden ayrıştırılır. Tanınan bir efekt belirtilmemişse, [InkEffectType::NotDefined](../../inkeffecttype/) döndürülür.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Açıklamalar

Örnek: ```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Ayrıca Bakınız

* Enum [InkEffectType](../../inkeffecttype/)
* Sınıf [IInkBrush](../)
* İsim alanı [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)