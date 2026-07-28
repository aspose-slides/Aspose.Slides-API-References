---
title: BuildObject()
second_title: Aspose.Slides dla interfejsu API C++
description: Utwórz obiekt ze współdzielonym własnictwem.
type: docs
weight: 2250
url: /pl/system/buildobject/
---
## System::BuildObject(Args\&&...) function

Zbuduj obiekt ze współdzielonym właścicielstwem.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu do zbudowania |
| Args | Typy argumentów dla konstrukcji obiektu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | Args\&&... | Argumenty przekazywane do konstruktora obiektu |

### Wartość zwracana

ObjectBuilder skonfigurowany do konstrukcji wskaźnika współdzielonego
## Uwagi

Tworzy SharedPtr<T> i zwraca konstruktor dla niego [Object](../object/) konstrukcja musi być zakończona wywołaniem [Get()](../get/)

## Zobacz także

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)