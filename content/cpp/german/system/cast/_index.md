---
title: Cast()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt einen Cast auf SmartPtr-Objekten aus.
type: docs
weight: 2510
url: /de/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) Funktion

Führt einen Cast auf [SmartPtr](../smartptr/) Objekten aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Pointee-Typ. |
| TFrom | Quell-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Quellzeiger. |

### Rückgabewert

Cast-Ergebnis, wenn der Cast erlaubt ist.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)