---
title: CheckWriteProtection()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda je prezentace chráněna heslem pro úpravy.
type: docs
weight: 157
url: /cs/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) metoda

Určuje, zda je prezentace chráněna heslem pro úpravy.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Heslo pro ověření. |

### Návratová hodnota

True pokud je heslo platné; v opačném případě false.

## Poznámky

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Měli byste zkontrolovat vlastnost [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) před voláním této metody.
2. Když je heslo null nebo prázdné, tato metoda vrací false.

## Viz také

* Třída [String](../../../system/string/)
* Třída [ProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)