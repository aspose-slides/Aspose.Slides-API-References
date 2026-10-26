---
title: GetMember()
second_title: Aspose.Slides für C++ API-Referenz
description: Erhält die Liste der Mitglieder mit dem angegebenen Namen.
type: docs
weight: 495
url: /de/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const Methode


Gibt die Liste der Mitglieder mit dem angegebenen Namen zurück.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../string/)\& | Name des Mitglieds, das abgerufen werden soll. |

### Rückgabewert

[Array](../../array/) von Mitgliedsbeschreibungen (leer, wenn kein Mitglied gefunden wurde).

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [MemberInfo](../../../system.reflection/memberinfo/)
* Klasse [String](../../string/)
* Klasse [TypeInfo](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)