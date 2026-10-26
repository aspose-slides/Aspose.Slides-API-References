---
title: GetEffective()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i dati di formattazione dello stile di testo effettivo con l'ereditarietà applicata.
type: docs
weight: 27
url: /it/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() metodo

Ottiene i dati di formattazione dello stile di testo effettivo con l'ereditarietà applicata.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Valore restituito

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).

## Osservazioni



Questo esempio dimostra come ottenere alcune delle proprietà dello stile di testo effettivo. 
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Classe [TextStyle](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)