---
title: ForceStaticCast()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt einen echten statischen Cast auf SmartPtr-Objekten aus.
type: docs
weight: 2588
url: /de/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) Funktion

Führt einen echten statischen Cast auf [SmartPtr](../smartptr/)-Objekten aus.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Pointee-Typ. |
| TFrom | Quell-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Quellzeiger. |

### Rückgabewert

Das Cast-Ergebnis, falls der Cast erlaubt ist; andernfalls ist das Verhalten undefiniert.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Struktur [CastResult](../castresult/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)