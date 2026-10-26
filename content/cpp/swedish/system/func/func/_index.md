---
title: Func()
second_title: Aspose.Slides för C++ API-referens
description: Standardkonstruktor som skapar null-Func.
type: docs
weight: 1
url: /sv/system/func/func/
---
## Func::Func() konstruktor

Standardkonstruktor som skapar null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) konstruktor

Konstruktor som skapar ett [Func](../)-objekt och tilldelar ett värde (antingen en faktisk återuppringning eller nullptr) till det.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Argumenttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg | T\&& | Argument. |

## Func::Func(const Func\&) konstruktor

Kopieringskonstruktor.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) att kopiera data från. |

## Func::Func(Func\&&) konstruktor

Flyttkonstruktor.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) att flytta data från. |

## Se även

* Klass [Func](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)