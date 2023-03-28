---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API Reference
description: Sets read-only recommendation. Write bool.
type: docs
weight: 92
url: /cpp/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(**bool**) method


Sets read-only recommendation. Write **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Remarks


The following sample code shows you how to set a PowerPoint [Presentation](../../presentation/) to Read-Only in C# using [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## See Also

* Class [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
