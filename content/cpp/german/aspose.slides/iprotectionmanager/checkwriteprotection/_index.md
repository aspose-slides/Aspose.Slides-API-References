---
title: CheckWriteProtection()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob eine Präsentation passwortgeschützt ist, um geändert zu werden.
type: docs
weight: 157
url: /de/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) Methode

Bestimmt, ob eine Präsentation passwortgeschützt ist, um geändert zu werden.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Das Passwort zum Überprüfen. |

### Rückgabewert

True, wenn das Passwort gültig ist; andernfalls false.

## Hinweise

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Sie sollten die [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/)-Eigenschaft prüfen, bevor Sie diese Methode aufrufen.
2. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)