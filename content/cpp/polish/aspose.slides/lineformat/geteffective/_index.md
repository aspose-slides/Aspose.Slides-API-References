---
title: GetEffective()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera skuteczne dane formatowania linii z zastosowanym dziedziczeniem.
type: docs
weight: 417
url: /pl/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() metoda

Pobiera skuteczne dane formatowania linii z zastosowanym dziedziczeniem.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### Wartość zwracana

A [ILineFormatEffectiveData](../../ilineformateffectivedata/).

## Uwagi

Ten przykład pokazuje pobieranie skutecznych właściwości formatu linii kształtu.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Class [LineFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)