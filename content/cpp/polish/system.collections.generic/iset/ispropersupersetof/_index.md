---
title: IsProperSupersetOf()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Sprawdza, czy bieżący zestaw jest ścisłym nadzbiorem innego kontenera.
type: docs
weight: 53
url: /pl/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) metoda


Sprawdza, czy bieżący zestaw jest ścisłym nadzbiorem innego kontenera.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | Podzbiór, względem którego sprawdzany jest zestaw. |

### Wartość zwracana

Prawda, jeśli wszystkie elementy w **other** są obecne w zestawie i zestaw ma więcej elementów niż **other**, w przeciwnym razie fałsz.

## Zobacz także

* Definicja typu [IEnumerablePtr](../ienumerableptr/)
* Klasa [ISet](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)