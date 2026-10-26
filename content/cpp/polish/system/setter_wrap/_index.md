---
title: setter_wrap()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Przeciążenie dla statycznych funkcji ustawiających z konwersją typu.
type: docs
weight: 2822
url: /pl/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) function

Przeciążenie dla statycznych funkcji ustawiających z konwersją typu.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości. |
| T2 | Typ oczekiwany przez funkcję ustawiającą. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pSetter | void(*)(T2) | Referencja do statycznej funkcji ustawiającej. |
| value | T | Wartość do ustawienia. |

### Wartość zwracana

ustawiona wartość.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) function

Przeciążenie dla funkcji ustawiających instancji z konwersją typu.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości. |
| T2 | Typ oczekiwany przez funkcję ustawiającą. |
| Host | Typ instancji. |
| HostSet | - Sam Host lub jego typ bazowy, w którym zdefiniowano setter właściwości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | Host *const | [Object](../object/) do wywołania funkcji ustawiającej. |
| pSetter | void(HostSet::*)(T2) | Referencja do funkcji ustawiającej. |
| value | T | Wartość do ustawienia. |

### Wartość zwracana

ustawiona wartość.

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)