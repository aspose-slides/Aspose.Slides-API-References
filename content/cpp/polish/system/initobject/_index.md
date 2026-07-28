---
title: InitObject()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Rozpoczyna inicjalizację obiektu ze współdzieloną własnością.
type: docs
weight: 2263
url: /pl/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) funkcja

Rozpoczyna inicjalizację obiektu ze współdzieloną własnością.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu do zainicjalizowania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) do zainicjalizowania |

### Wartość zwracana

ObjectBuilder skonfigurowany do tworzenia wskaźnika współdzielonego

## Uwagi

[Object](../object/) inicjalizacja musi zostać zakończona wywołaniem [Get()](../get/) call

## Zobacz także

* Definicja typu [SharedPtr](../sharedptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)