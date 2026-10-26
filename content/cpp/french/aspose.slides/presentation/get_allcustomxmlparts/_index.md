---
title: get_AllCustomXmlParts()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne toutes les parties de données personnalisées dans la présentation. Lecture seule ICustomXmlPart[].
type: docs
weight: 287
url: /fr/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() méthode

Retourne toutes les parties de données personnalisées dans la présentation. Lecture seule [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Remarques

Les exemples suivants montrent comment supprimer toutes les parties xml personnalisées de PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICustomXmlPart](../../icustomxmlpart/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)