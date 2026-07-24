---
title: GetEffective()
second_title: Aspose.Slides için C++ API Referansı
description: Kalıtım uygulanmış etkili arka plan verilerini alır.
type: docs
weight: 118
url: /tr/aspose.slides/background/geteffective/
---
## Background::GetEffective() metodu

Kalıtım uygulanmış etkili arka plan verilerini alır.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### Dönüş Değeri

A [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## Açıklamalar

Bu örnek, etkili arka plan özelliklerinin alınmasını gösterir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Sınıf [Background](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)