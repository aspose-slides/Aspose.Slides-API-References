---
title: Encrypt()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Šifruje prezentaci pomocí zadaného hesla.
type: docs
weight: 105
url: /cs/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) metoda

Šifruje [Presentation](../../presentation/) pomocí zadaného hesla.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Heslo. |

## Poznámky

Následující ukázkový kód vám ukazuje, jak šifrovat PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [ProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)