---
title: SetWriteProtection()
second_title: Aspose.Slides C++ API referencia
description: Beállítja a írásvédelmet ehhez a bemutatóhoz a megadott jelszóval.
type: docs
weight: 131
url: /hu/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) metódus


Állítsa be a biztonsági írásvédelmet ehhez a bemutatóhoz a megadott jelszóval.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A jelszó. |
## Megjegyzések



Az alábbi minta kód bemutatja, hogyan állíthat be írásvédelmet egy bemutatóhoz. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ProtectionManager](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)