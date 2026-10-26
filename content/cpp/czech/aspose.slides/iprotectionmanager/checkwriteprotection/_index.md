---
title: CheckWriteProtection()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda je prezentace chráněna heslem pro úpravu.
type: docs
weight: 157
url: /cs/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) metoda

Určuje, zda je prezentace chráněna heslem pro úpravu.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Heslo pro kontrolu. |

### Návratová hodnota

True, pokud je heslo platné; jinak false.

## Poznámky

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Měli byste zkontrolovat vlastnost [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) před voláním této metody.
1. Když je heslo null nebo prázdné, tato metoda vrací false.

## Viz také

* Třída [String](../../../system/string/)
* Třída [IProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)