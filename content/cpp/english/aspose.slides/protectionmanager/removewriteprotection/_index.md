---
title: RemoveWriteProtection()
second_title: Aspose.Slides for C++ API Reference
description: Removes write protection for this presentation.
type: docs
weight: 144
url: /aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() method


Removes write protection for this presentation.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Remarks


This sample code shows you how to remove the write protection from a PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## See Also

* Class [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)