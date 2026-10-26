---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API Referenz
description: Liest die Empfehlung für Nur-Lesen. bool auslesen.
type: docs
weight: 79
url: /de/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() Methode


Liest die Empfehlung für Nur-Lesen. Lese **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Bemerkungen


Der folgende Beispielcode zeigt, wie Sie ein PowerPoint [Presentation](../../presentation/) in C# mit [Aspose.Slides](../../) auf Nur-Lesen setzen.
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [ProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)