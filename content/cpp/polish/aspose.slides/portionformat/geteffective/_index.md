---
title: GetEffective()
second_title: Referencja API Aspose.Slides dla C++
description: Pobiera efektywne dane formatowania części z uwzględnieniem dziedziczenia.
type: docs
weight: 131
url: /pl/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() metoda


Pobiera efektywne dane formatowania części z uwzględnieniem dziedziczenia.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Wartość zwracana

A [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Uwagi



Ten przykład demonstruje pobieranie niektórych właściwości efektywnego formatu części. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Klasa [PortionFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)