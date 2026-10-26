---
title: GetMember()
second_title: Aspose.Slides C++ API-referencia
description: A megadott névvel rendelkező tagok listáját adja vissza.
type: docs
weight: 495
url: /hu/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const metódus

A megadott névvel rendelkező tagok listáját adja vissza.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../string/)\& | A lekérdezendő tag neve. |

### Visszatérési érték

[Array](../../array/) a tag leírók (üres, ha nem található tag).

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [MemberInfo](../../../system.reflection/memberinfo/)
* Osztály [String](../../string/)
* Osztály [TypeInfo](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)