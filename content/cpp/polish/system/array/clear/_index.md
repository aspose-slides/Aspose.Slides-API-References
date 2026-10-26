---
title: Clear()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Nieobsługiwane, ponieważ tablica reprezentowana przez bieżący obiekt jest tylko do odczytu.
type: docs
weight: 53
url: /pl/system/array/clear/
---
## Array::Clear() metoda

Nie jest obsługiwane, ponieważ tablica reprezentowana przez bieżący obiekt jest tylko do odczytu.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) metoda

Zastępuje **count** wartości począwszy od indeksu **startIndex** w określonej tablicy wartościami domyślnymi.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Type | Typ elementów w docelowej tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Docelowa tablica |
| startIndex | int | [Index](../../index/) określający, od którego miejsca rozpocząć zastępowanie elementów |
| count | int | Liczba elementów do zastąpienia |

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Metoda [Type](../../object/type/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)