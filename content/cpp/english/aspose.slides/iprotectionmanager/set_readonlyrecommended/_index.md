---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API Reference
description: Sets read-only recommendation. Write bool.
type: docs
weight: 92
url: /aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) method


Sets read-only recommendation. Write **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## See Also

* Class [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)