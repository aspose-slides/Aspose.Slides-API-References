---
title: RemoveWriteProtection()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Usuwa ochronę zapisu dla tej prezentacji.
type: docs
weight: 144
url: /pl/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() metoda


Usuwa ochronę zapisu dla tej prezentacji.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Uwagi


Ten przykładowy kod pokazuje, jak usunąć ochronę zapisu z pliku PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [ProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)