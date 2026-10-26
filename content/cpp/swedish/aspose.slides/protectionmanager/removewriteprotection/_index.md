---
title: RemoveWriteProtection()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort skrivskydd för den här presentationen.
type: docs
weight: 144
url: /sv/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() metod


Tar bort skrivskydd för den här presentationen.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Anmärkningar


Detta exempel på kod visar hur du tar bort skrivskyddet från en PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [ProtectionManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)