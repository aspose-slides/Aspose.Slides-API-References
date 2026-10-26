---
title: GetEffective()
second_title: Aspose.Slides C++ için API Referansı
description: Kalıtım uygulanmış etkili çizgi biçimlendirme verilerini alır.
type: docs
weight: 417
url: /tr/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() method


Kalıtım uygulanmış etkili çizgi biçimlendirme verilerini alır.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Dönüş Değeri

A [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Açıklamalar



Bu örnek, şeklin etkili çizgi biçim özelliklerini almayı gösterir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Class [LineFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)