---
title: GetEffective()
second_title: Aspose.Slides for C++ API referencia
description: Lekéri a hatékony részformázási adatokat az öröklődés alkalmazásával.
type: docs
weight: 131
url: /hu/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() metódus


Lekéri a hatékony részformázási adatokat az öröklődés alkalmazásával.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Visszatérési érték

Egy [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Megjegyzések



Ez a példa bemutatja, hogyan kérhet le néhány hatékony részformátum tulajdonságot. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Osztály [PortionFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)