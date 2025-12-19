---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API Reference
description: Gets read-only recommendation. Read bool.
type: docs
weight: 79
url: /aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() method


Gets read-only recommendation. Read **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
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