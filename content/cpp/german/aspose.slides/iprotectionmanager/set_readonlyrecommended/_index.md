---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Empfehlung für schreibgeschützt. Schreiben bool.
type: docs
weight: 92
url: /de/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) Methode

Setzt die Empfehlung für schreibgeschützt. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)