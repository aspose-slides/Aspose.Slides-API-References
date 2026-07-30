---
title: setter_post_increment_wrap()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Překladač převádí postinkrementační výrazy C# zaměřené na vlastnost třídy, která má definované setter a getter, na volání této funkce.
type: docs
weight: 2848
url: /cs/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) function

Překladač převádí postinkrementační výrazy C# cílené na vlastnost třídy, která má definované setter a getter, na volání této funkce.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ vlastnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pGetter | T(*)() | Ukazatel na funkci ukazující na getter volnou funkci vlastnosti |
| pSetter | void(*)(T) | Ukazatel na funkci ukazující na setter volnou funkci vlastnosti |

### Návratová hodnota

Hodnota vlastnosti před inkrementací

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function

Překladač převádí postinkrementační výrazy C# cílené na vlastnost instance, která má definované setter a getter, na volání této funkce (přetížení pro ne-konstantní getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ vlastnosti. |
| Host | - třída instance, která má být upravena |
| HostGet | - Host samotný nebo jeho základní typ, kde je definován getter vlastnosti |
| HostSet | - Host samotný nebo jeho základní typ, kde je definován setter vlastnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | Host *const | Instance, pro kterou se volají gettery a settery. |
| pGetter | T(HostGet::*)() | Ukazatel na funkci ukazující na getter funkci vlastnosti |
| pSetter | void(HostSet::*)(T) | Ukazatel na funkci ukazující na setter funkci vlastnosti |

### Návratová hodnota

Hodnota vlastnosti před inkrementací

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function

Překladač převádí postinkrementační výrazy C# cílené na vlastnost instance, která má definované setter a getter, na volání této funkce (přetížení pro konstantní getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ vlastnosti. |
| Host | - třída instance, která má být upravena |
| HostConstGet | - Host samotný nebo jeho základní typ, kde je definován getter vlastnosti |
| HostSet | - Host samotný nebo jeho základní typ, kde je definován setter vlastnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | Host *const | Instance, pro kterou se volají gettery a settery. |
| pGetter | T(HostConstGet::*)() const | Ukazatel na funkci ukazující na getter funkci vlastnosti |
| pSetter | void(HostSet::*)(T) | Ukazatel na funkci ukazující na setter funkci vlastnosti |

### Návratová hodnota

Hodnota vlastnosti před inkrementací

## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)