---
title: GetEffective()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata.
type: docs
weight: 365
url: /it/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() metodo


Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Valore restituito

A [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Note



Questo esempio dimostra come ottenere alcune proprietà di formattazione del paragrafo effettive. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Classe [ParagraphFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)