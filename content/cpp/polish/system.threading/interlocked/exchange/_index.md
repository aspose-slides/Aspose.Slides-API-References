---
title: Exchange()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Wymienia wartość zmiennej: zapisuje nową wartość i zwraca wartość, jaką zmienna miała bezpośrednio przed zapisem."
type: docs
weight: 66
url: /pl/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) metoda


Wymienia wartość zmiennej: zapisuje nową wartość i zwraca wartość, jaką zmienna miała bezpośrednio przed zapisem.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ zmiennej. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| location1 | T\& | Referencja do zmiennej do zmiany. |
| value | T | Wartość do zapisania. |

### Wartość zwracana

Wartość zmiennej tuż przed jej zmianą.

## Interlocked::Exchange(T\&, T) metoda


Wymienia wartość zmiennej: zapisuje nową wartość i zwraca wartość, jaką zmienna miała bezpośrednio przed zapisem. Nie zaimplementowano.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ zmiennej. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| location1 | T\& | Referencja do zmiennej do zmiany. |
| value | T | Wartość do zapisania. |

### Wartość zwracana

Wartość zmiennej tuż przed jej zmianą.

## Zobacz także

* Klasa [Interlocked](../)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)