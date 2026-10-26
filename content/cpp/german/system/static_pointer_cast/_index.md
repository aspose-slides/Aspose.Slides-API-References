---
title: static_pointer_cast()
second_title: Aspose.Slides für C++ API-Referenz
description: Wandelt Smart-Pointer mittels static_cast um.
type: docs
weight: 2913
url: /de/system/static_pointer_cast/
---
## System::static_pointer_cast(SmartPtr\<X\> const\&) Funktion

Wandelt Smart-Pointer mittels static_cast um.

```cpp
template<class Y,class X> SmartPtr<Y> System::static_pointer_cast(SmartPtr<X> const &x)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| X | Typ des Zeigerobjekts, auf das der Quellzeiger zeigt. |
| Y | Typ des Zeigerobjekts, auf das der Zielzeiger zeigt. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Quellzeiger. |

### Rückgabewert

Zeiger nach dem Cast.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)