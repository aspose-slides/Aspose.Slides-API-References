---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API referencia
description: Lekéri az írásvédett ajánlást. Olvas bool.
type: docs
weight: 79
url: /hu/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() metódus

Lekéri az írásvédett ajánlást. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IProtectionManager](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)