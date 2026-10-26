---
title: GetEffective()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera efektywne dane formatowania akapitu z zastosowanym dziedziczeniem.
type: docs
weight: 365
url: /pl/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() metoda

Pobiera efektywne dane formatowania akapitu z zastosowanym dziedziczeniem.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### Wartość zwracana

Obiekt [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Uwagi



Ten przykład pokazuje pobieranie niektórych efektywnych właściwości formatu akapitu. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Klasa [ParagraphFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)