---
title: operator<()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zapewnia semantykę porównania mniejszego dla klasy SmartPtr.
type: docs
weight: 235
url: /pl/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method

Zapewnia semantykę porównania mniejszego dla klasy [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Typ wskaźnika, z którym porównywany jest bieżący. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| p | Y * | Wskaźnik do porównania z bieżącym. |

### Wartość zwracana

prawda, jeśli obiekt referencjonowany przez [SmartPtr](../) jest 'mniejszy' niż p, w przeciwnym razie fałsz.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method

Zapewnia semantykę porównania mniejszego dla klasy [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Typ wskaźnika, z którym porównywany jest bieżący. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Wskaźnik do porównania z bieżącym. |

### Wartość zwracana

prawda, jeśli obiekt referencjonowany przez [SmartPtr](../) jest 'mniejszy' niż x, w przeciwnym razie fałsz.

## Zobacz także

* Klasa [SmartPtr](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)