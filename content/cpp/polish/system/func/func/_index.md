---
title: Func()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Domyślny konstruktor, który tworzy null-Func.
type: docs
weight: 1
url: /pl/system/func/func/
---
## Func::Func() konstruktor


Domyślny konstruktor, który tworzy null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) konstruktor


Konstruktor, który tworzy obiekt [Func](../) i przypisuje mu wartość (rzeczywiste wywołanie zwrotne lub nullptr).

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ argumentu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arg | T\&& | Argument. |

## Func::Func(const Func\&) konstruktor


Konstruktor kopiujący.

```cpp
System::Func<Args>::Func(const Func &func)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) do skopiowania danych z. |

## Func::Func(Func\&&) konstruktor


Konstruktor przenoszący.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) do przeniesienia danych z. |

## Zobacz także

* Klasa [Func](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)