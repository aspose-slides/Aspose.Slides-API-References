---
title: RemoveWriteProtection()
second_title: Aspose.Slides für C++ API Referenz
description: Entfernt den Schreibschutz für diese Präsentation.
type: docs
weight: 144
url: /de/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() Methode


Entfernt den Schreibschutz für diese Präsentation.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Hinweise


Dieser Beispielcode zeigt, wie der Schreibschutz von einer PowerPoint [Presentation](../../presentation/) entfernt wird. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [ProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)