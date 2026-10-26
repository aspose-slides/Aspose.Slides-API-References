---
title: GetUnderlyingType()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das zugrunde liegende Typ-Argument des angegebenen nullable Typs zurück.
type: docs
weight: 1
url: /de/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) Methode

Gibt das zugrunde liegende Typ-Argument des angegebenen nullable Typs zurück.

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | Ein System.Type-Objekt, das einen abgeschlossenen generischen nullable Typ beschreibt. |

### Rückgabewert

Das Typ-Argument des nullableType-Parameters, falls der nullableType-Parameter ein abgeschlossener generischer nullable Typ ist; andernfalls null

## Siehe auch

* Klasse [TypeInfo](../../typeinfo/)
* Klasse [NullableUtils](../)
* Namespace [System](../../)
* Bibliothek [Aspose.Slides](../../../)