---
title: Func()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Výchozí konstruktor, který vytvoří null-Func.
type: docs
weight: 1
url: /cs/system/func/func/
---
## Func::Func() konstruktor

Výchozí konstruktor, který vytvoří null-Func.

```cpp
System::Func<Args>::Func()
```
## Func::Func(T\&&) konstruktor

Konstruktor, který vytvoří objekt [Func](../) a přiřadí mu hodnotu (buď skutečný callback nebo nullptr).

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```
### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ argumentu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arg | T\&& | Argument. |

## Func::Func(const Func\&) konstruktor

Kopírovací konstruktor.

```cpp
System::Func<Args>::Func(const Func &func)
```
### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) pro kopírování dat z. |

## Func::Func(Func\&&) konstruktor

Přesunovací konstruktor.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```
### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) pro přesunutí dat z. |

## Viz také

* Třída [Func](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)