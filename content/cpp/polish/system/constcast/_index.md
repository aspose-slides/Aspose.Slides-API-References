---
title: ConstCast()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Koniec przestarzałych rzutowań.
type: docs
weight: 2575
url: /pl/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) funkcja

Koniec przestarzałych rzutowań.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Typ wskaźnika docelowego. |
| TFrom | Typ wskaźnika źródłowego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone, lub nullptr w przeciwnym razie.

## Uwagi

Wykonuje rzutowanie const na obiektach [SmartPtr](../smartptr/).

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Struktura [CastResult](../castresult/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)