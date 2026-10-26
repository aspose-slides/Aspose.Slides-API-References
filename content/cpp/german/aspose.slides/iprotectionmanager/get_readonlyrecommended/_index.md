---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die schreibgeschützte Empfehlung. Liest bool.
type: docs
weight: 79
url: /de/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() Methode


Ermittelt die schreibgeschützte Empfehlung. Liest **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Anmerkungen



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)