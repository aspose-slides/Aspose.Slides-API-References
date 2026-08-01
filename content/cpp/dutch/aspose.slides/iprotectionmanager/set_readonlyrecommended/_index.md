---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de alleen-lezen aanbeveling in. Schrijf bool.
type: docs
weight: 92
url: /nl/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) methode

Stelt de alleen-lezen aanbeveling in. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IProtectionManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)