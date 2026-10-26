---
title: RemoveWriteProtection()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja az írásvédelmet erről a bemutatóról.
type: docs
weight: 144
url: /hu/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() metódus


Eltávolítja az írásvédelmet erről a bemutatóról.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Megjegyzések


Ez a mintakód megmutatja, hogyan lehet eltávolítani az írásvédelmet egy PowerPoint [Presentation](../../presentation/)-ból.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [ProtectionManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)