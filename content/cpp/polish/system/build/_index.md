---
title: Build()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Utwórz obiekt z bezpośrednią własnością.
type: docs
weight: 2289
url: /pl/system/build/
---
## System::Build(Args&&...) funkcja


Utwórz obiekt z bezpośrednią własnością.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu do zbudowania |
| Args | Typy argumentów dla konstrukcji obiektu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | Args&&... | Argumenty do przekazania do konstruktora obiektu |

### Wartość zwracana

ObjectBuilder skonfigurowany do bezpośredniej konstrukcji obiektu
## Uwagi



[Object](../object/) konstrukcja musi zostać zakończona wywołaniem [Get()](../get/) 

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)