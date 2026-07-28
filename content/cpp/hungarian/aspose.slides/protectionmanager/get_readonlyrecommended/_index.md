---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a csak-olvasás ajánlását. Olvas bool.
type: docs
weight: 79
url: /hu/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() metódus


Lekéri a csak-olvasás ajánlását. Olvas **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Megjegyzések


A következő példakód bemutatja, hogyan állíthat be egy PowerPoint [Presentation](../../presentation/)-t csak-olvasásra C#-ban a [Aspose.Slides](../../) használatával. 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [ProtectionManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)