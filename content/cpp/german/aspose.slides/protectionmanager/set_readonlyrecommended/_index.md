---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides für C++ API Referenz
description: Setzt die Empfehlung für schreibgeschützt. Schreib bool.
type: docs
weight: 92
url: /de/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) Methode


Setzt die Empfehlung für schreibgeschützt. Schreib **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Hinweise


Der folgende Beispielcode zeigt, wie Sie ein PowerPoint [Presentation](../../presentation/) in C# mit [Aspose.Slides](../../) auf Schreibgeschützt setzen.
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [ProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)