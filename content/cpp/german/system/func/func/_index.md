---
title: Func()
second_title: Aspose.Slides für C++ API-Referenz
description: Standardkonstruktor, der einen null-Func erstellt.
type: docs
weight: 1
url: /de/system/func/func/
---
## Func::Func() Konstruktor


Standardkonstruktor, der einen null-Func erstellt.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) Konstruktor


Konstruktor, der ein [Func](../)-Objekt erstellt und ihm einen Wert zuweist (entweder tatsächlichen Callback oder nullptr).

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Argumenttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg | T\&& | Argument. |

## Func::Func(const Func\&) Konstruktor


Kopierkonstruktor.

```cpp
System::Func<Args>::Func(const Func &func)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) zum Kopieren der Daten von. |

## Func::Func(Func\&&) Konstruktor


Move-Konstruktor.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) zum Verschieben der Daten von. |

## Siehe auch

* Klasse [Func](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)