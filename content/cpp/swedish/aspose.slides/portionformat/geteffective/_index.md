---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiv portionformateringsdata med ärftlighet tillämpad.
type: docs
weight: 131
url: /sv/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() metod


Hämtar effektiv portionformateringsdata med ärftlighet tillämpad.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Returvärde

En [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Anmärkningar



Detta exempel visar hur man hämtar vissa effektiva portionformategenskaper. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Klass [PortionFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)