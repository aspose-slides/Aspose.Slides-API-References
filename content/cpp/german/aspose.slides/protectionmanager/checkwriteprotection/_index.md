---
title: CheckWriteProtection()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, ob eine Präsentation passwortgeschützt ist, um sie zu ändern.
type: docs
weight: 157
url: /de/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) Methode

Bestimmt, ob eine Präsentation passwortgeschützt ist, um sie zu ändern.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Das Passwort zur Überprüfung. |

### Rückgabewert

Wahr, wenn das Passwort gültig ist; andernfalls falsch.

## Bemerkungen

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Sie sollten die Eigenschaft [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) überprüfen, bevor Sie diese Methode aufrufen.
1. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)