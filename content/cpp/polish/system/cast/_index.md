---
title: Cast()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wykonuje rzutowanie na obiektach SmartPtr.
type: docs
weight: 2510
url: /pl/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) funkcja


Wykonuje rzutowanie na obiektach [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Docelowy typ wskaźnika. |
| TFrom | Źródłowy typ wskaźnika. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)