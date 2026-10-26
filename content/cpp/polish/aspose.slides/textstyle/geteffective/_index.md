---
title: GetEffective()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Pobiera efektywne dane formatowania stylu tekstu z zastosowanym dziedziczeniem.
type: docs
weight: 27
url: /pl/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() metoda


Pobiera efektywne dane formatowania stylu tekstu z zastosowanym dziedziczeniem.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Wartość zwracana

Obiekt [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Uwagi



Ten przykład demonstruje pobieranie niektórych efektywnych właściwości stylu tekstu. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Klasa [TextStyle](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)