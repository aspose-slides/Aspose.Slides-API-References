---
title: ForceStaticCast()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Wykonuje rzeczywiste rzutowanie statyczne na obiektach SmartPtr.
type: docs
weight: 2588
url: /pl/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const&) funkcja

Wykonuje rzeczywiste rzutowanie statyczne na obiektach [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Docelowy typ wskazywanego obiektu. |
| TFrom | Źródłowy typ wskazywanego obiektu. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone, w przeciwnym razie zachowanie jest nieokreślone.

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Struktura [CastResult](../castresult/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)