---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce tutte le parti di dati personalizzate nella presentazione. Solo lettura ICustomXmlPart[].
type: docs
weight: 287
url: /it/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() metodo

Restituisce tutte le parti di dati personalizzate nella presentazione. Solo lettura [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Osservazioni

Gli esempi seguenti mostrano come cancellare tutte le parti xml personalizzate da PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Itera tutte le parti XML personalizzate
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICustomXmlPart](../../icustomxmlpart/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)