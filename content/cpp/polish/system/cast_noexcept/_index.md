---
title: Cast_noexcept()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Wykonuje rzutowanie obiektów SmartPtr.
type: docs
weight: 2497
url: /pl/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) funkcja

Wykonuje rzutowanie obiektów [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ wskaźnika. |
| TFrom | Źródłowy typ wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone, lub nullptr w przeciwnym wypadku.

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)