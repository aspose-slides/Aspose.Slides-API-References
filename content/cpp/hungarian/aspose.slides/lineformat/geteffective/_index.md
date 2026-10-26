---
title: GetEffective()
second_title: Aspose.Slides for C++ API hivatkozás
description: Visszaadja a származtatással alkalmazott hatékony vonalformázási adatokat.
type: docs
weight: 417
url: /hu/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() metódus

A származtatással alkalmazott hatékony vonalformázási adatokat adja vissza.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### Visszatérési érték

Egy [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Megjegyzések

Ez a példa bemutatja, hogyan lehet lekérni az alakzat hatékony vonalformázási tulajdonságait.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Osztály [LineFormat](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)