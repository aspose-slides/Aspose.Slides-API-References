---
title: DynamicCastArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt das Casting von Elementen des angegebenen Arrays in einen anderen Typ durch.
type: docs
weight: 2991
url: /de/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) Funktion

Führt das Casting von Elementen des angegebenen Arrays in einen anderen Typ durch.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| To | Der Typ, in den die Elemente des angegebenen Arrays gecastet werden sollen |
| From | Der Typ der Elemente des Arrays, deren Elemente gecastet werden sollen |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Gemeinsamer Zeiger auf das Array, das die zu castenden Elemente enthält |

### Rückgabewert

Ein Zeiger auf ein neues Array, das Elemente vom Typ **To** enthält, die den Elementen von **from** entsprechen

Veraltet
:   Hinzugefügt für die Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Klasse [Array](../array/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)