---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een alleen-lezen aanbeveling in. Schrijf bool.
type: docs
weight: 92
url: /nl/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) methode

Stelt een aanbeveling voor alleen-lezen in. Schrijf **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Opmerkingen

De volgende voorbeeldcode laat zien hoe u een PowerPoint [Presentation](../../presentation/) op Alleen-lezen instelt in C# met [Aspose.Slides](../../).
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)