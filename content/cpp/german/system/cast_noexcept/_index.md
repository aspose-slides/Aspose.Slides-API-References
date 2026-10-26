---
title: Cast_noexcept()
second_title: Aspose.Slides für C++ API Referenz
description: Führt einen Cast auf SmartPtr-Objekten aus.
type: docs
weight: 2497
url: /de/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) Funktion

Führt einen Cast für [SmartPtr](../smartptr/) Objekte aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
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

Cast-Ergebnis, wenn der Cast erlaubt ist, sonst nullptr.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)