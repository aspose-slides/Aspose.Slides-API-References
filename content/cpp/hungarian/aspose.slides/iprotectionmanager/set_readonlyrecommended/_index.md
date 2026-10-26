---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API referencia
description: Beállítja az írásvédett ajánlást. Írja bool.
type: docs
weight: 92
url: /hu/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) metódus


Beállítja az írásvédett ajánlást. Írja **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IProtectionManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)