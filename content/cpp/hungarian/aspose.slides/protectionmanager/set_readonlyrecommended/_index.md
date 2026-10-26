---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API hivatkozás
description: Beállítja a csak olvasható ajánlást. Írja a bool értéket.
type: docs
weight: 92
url: /hu/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) metódus

Beállítja a csak olvasható ajánlást. Írja **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Megjegyzések

A következő mintakód megmutatja, hogyan állítható be egy PowerPoint [Presentation](../../presentation/) csak olvasható módra C#-ban a [Aspose.Slides](../../) segítségével.
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [ProtectionManager](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)