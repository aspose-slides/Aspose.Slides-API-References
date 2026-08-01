---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de alleen-lezen aanbeveling op. Lezen bool.
type: docs
weight: 79
url: /nl/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() methode


Haalt de alleen-lezen aanbeveling op. Lezen **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
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