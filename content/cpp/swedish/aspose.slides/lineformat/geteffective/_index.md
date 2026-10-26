---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiv linjeformateringsdata med arv tillämpat.
type: docs
weight: 417
url: /sv/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() metod


Hämtar effektiv linjeformateringsdata med arv tillämpat.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Returvärde

En [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Anmärkningar



Detta exempel demonstrerar hur man hämtar formens effektiva linjeformatsegenskaper. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Klass [LineFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)