---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna todas as partes de dados personalizadas na apresentação. Somente leitura ICustomXmlPart[].
type: docs
weight: 287
url: /pt/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() método


Retorna todas as partes de dados personalizadas na apresentação. Somente leitura [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Observações


Os exemplos a seguir mostram como limpar todas as partes xml personalizadas do PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICustomXmlPart](../../icustomxmlpart/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)