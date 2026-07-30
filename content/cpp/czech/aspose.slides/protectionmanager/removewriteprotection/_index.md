---
title: RemoveWriteProtection()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Odstraňuje ochranu proti zápisu pro tuto prezentaci.
type: docs
weight: 144
url: /cs/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() metoda


Odstraňuje ochranu proti zápisu pro tuto prezentaci.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Poznámky


Tento ukázkový kód vám ukazuje, jak odebrat ochranu proti zápisu z PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [ProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)