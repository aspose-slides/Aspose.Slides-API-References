---
title: IsDefined()
second_title: Aspose.Slides für C++ API-Referenz
description: NICHT IMPLEMENTIERT. Gibt an, ob ein oder mehrere Attribute des angegebenen Typs oder seiner abgeleiteten Typen auf dieses Mitglied angewendet werden.
type: docs
weight: 157
url: /de/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const Methode

NICHT IMPLEMENTIERT. Gibt an, ob ein oder mehrere Attribute des angegebenen Typs oder seiner abgeleiteten Typen auf dieses Mitglied angewendet werden.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Der Typ des benutzerdefinierten Attributs, nach dem gesucht wird. Die Suche umfasst abgeleitete Typen. |
| inherit | **bool** | true, um die Vererbungskette dieses Mitglieds zu durchsuchen und die Attribute zu finden; andernfalls false. Dieser Parameter wird für properties und events ignoriert. |

### Rückgabewert

true, wenn eine oder mehrere Instanzen von attributeType oder einem seiner abgeleiteten Typen auf dieses Mitglied angewendet werden; andernfalls false.

## Siehe auch

* Klasse [TypeInfo](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)