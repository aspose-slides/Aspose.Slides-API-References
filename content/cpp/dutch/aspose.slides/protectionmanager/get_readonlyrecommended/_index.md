---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de alleen-lezen aanbeveling op. Lezen bool.
type: docs
weight: 79
url: /nl/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() methode


Haalt de aanbeveling voor alleen-lezen op. Lezen **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Opmerkingen


De volgende voorbeeldcode laat zien hoe u een PowerPoint [Presentation](../../presentation/) op Alleen-lezen kunt instellen in C# met behulp van [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [ProtectionManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)