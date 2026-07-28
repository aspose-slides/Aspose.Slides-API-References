---
title: Default()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca referencję do jedynej domyślnie skonstruowanej instancji typu wyjątku.
type: docs
weight: 2224
url: /pl/system/default/
---
## System::Default() funkcja

Zwraca referencję do jedynej domyślnie skonstruowanej instancji typu wyjątku.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, którego instancja jest zwracana |

## System::Default() funkcja

Zwraca referencję do jedynej domyślnie skonstruowanej instancji typu nie-wyjątkowego.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, którego instancja jest zwracana |

## Zobacz także

* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)