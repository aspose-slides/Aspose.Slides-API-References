---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API Reference
description: Gets read-only recommendation. Read bool.
type: docs
weight: 79
url: /cpp/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() method


Gets read-only recommendation. Read **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
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