---
title: setter_wrap()
second_title: Aspose.Slides pro C++ - referenční dokumentace
description: Přetížení pro statické setter funkce s konverzí typu.
type: docs
weight: 2822
url: /cs/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) funkce

Přetížení pro statické setter funkce s konverzí typu.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty. |
| T2 | Typ očekávaný setter funkcí. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pSetter | void(*)(T2) | Reference na statickou setter funkci. |
| value | T | Hodnota k nastavení. |

### Návratová hodnota

nastavená hodnota.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) funkce

Přetížení pro instance setter funkce s konverzí typu.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty. |
| T2 | Typ očekávaný setter funkcí. |
| Host | Typ instance. |
| HostSet | - Host sám, nebo jeho základní typ, kde je definován setter vlastnosti. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | Host *const | [Object](../object/) pro volání setter funkce. |
| pSetter | void(HostSet::*)(T2) | Reference na setter funkci. |
| value | T | Hodnota k nastavení. |

### Návratová hodnota

nastavená hodnota.

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)