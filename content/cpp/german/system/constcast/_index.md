---
title: ConstCast()
second_title: Aspose.Slides für C++ API-Referenz
description: Ende veralteter Casts.
type: docs
weight: 2575
url: /de/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) Funktion

Ende veralteter Casts.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Pointee-Typ. |
| TFrom | Quell-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Quellzeiger. |

### Rückgabewert

Cast-Ergebnis, falls der Cast erlaubt ist, andernfalls nullptr.

## Bemerkungen

Führt einen const cast auf [SmartPtr](../smartptr/)-Objekten aus.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Struktur [CastResult](../castresult/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)