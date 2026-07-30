---
title: setter_increment_wrap()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Překladač překládá inkrementační výrazy C#, které cílí na vlastnost třídy s definovaným setterem a getterem, na volání této funkce.
type: docs
weight: 2835
url: /cs/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) funkce


Translator překládá C# increment výrazy cílící na vlastnost třídy, která má definovány setter a getter, na volání této funkce.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ vlastnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pGetter | T(*)() | Ukazatel na funkci ukazující na getter volné funkce vlastnosti |
| pSetter | void(*)(T) | Ukazatel na funkci ukazující na setter volné funkce vlastnosti |

### Návratová hodnota

Inkrementovaná hodnota vlastnosti

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funkce


Translator překládá C# increment výrazy cílící na vlastnost třídy, která má definovány setter a getter, na volání této funkce.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ vlastnosti |
| Host | - třída instance, která má být modifikována |
| HostGet | - Host sám, nebo jeho základní typ, kde je definován getter vlastnosti |
| HostSet | - Host sám, nebo jeho základní typ, kde je definován setter vlastnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | Host *const | Ukazatel na objekt, jehož vlastnost má být inkrementována |
| pGetter | T(HostGet::*)() | Ukazatel na funkci ukazující na metodu getteru vlastnosti |
| pSetter | void(HostSet::*)(T) | Ukazatel na funkci ukazující na metodu setteru vlastnosti |

### Návratová hodnota

Inkrementovaná hodnota vlastnosti

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)