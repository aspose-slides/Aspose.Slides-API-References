---
title: Encrypt()
second_title: Aspose.Slides C++ API Referenciája
description: Titkosítja a prezentációt a megadott jelszóval.
type: docs
weight: 105
url: /hu/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) metódus


Titkosítja a(z) [Presentation](../../presentation/)-t a megadott jelszóval.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | A jelszó. |
## Megjegyzés



Az alábbi példa kód megmutatja, hogyan titkosíthatja a PowerPoint [Presentation](../../presentation/)-t.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ProtectionManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)