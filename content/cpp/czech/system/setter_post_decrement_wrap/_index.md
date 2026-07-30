---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides pro C++ API Reference
description: Překladač překládá postdekrementační výrazy C# zaměřené na vlastnost třídy, která má definovány setter a getter, na volání této funkce.
type: docs
weight: 2874
url: /cs/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) funkce

Překladač překládá postdekrementační výrazy C# zaměřené na vlastnost třídy, která má definovány setter a getter, na volání této funkce.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ vlastnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pGetter | T(*)() | Ukazatel na funkci, který odkazuje na volnou funkci getteru vlastnosti |
| pSetter | void(*)(T) | Ukazatel na funkci, který odkazuje na volnou funkci setteru vlastnosti |

### Návratová hodnota

Hodnota vlastnosti před inkrementací

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funkce

Překladač překládá postdekrementační výrazy C# zaměřené na vlastnost instance, která má definovány setter a getter, na volání této funkce (přetížení pro getter bez const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
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
| pGetter | T(HostGet::*)() | Ukazatel na funkci, který odkazuje na funkci getteru vlastnosti |
| pSetter | void(HostSet::*)(T) | Ukazatel na funkci, který odkazuje na funkci setteru vlastnosti |

### Návratová hodnota

Hodnota vlastnosti před inkrementací

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) funkce

Překladač překládá postdekrementační výrazy C# zaměřené na vlastnost instance, která má definovány setter a getter, na volání této funkce (přetížení pro const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
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
| pGetter | T(HostConstGet::*)() const | Ukazatel na funkci, který odkazuje na funkci getteru vlastnosti |
| pSetter | void(HostSet::*)(T) | Ukazatel na funkci, který odkazuje na funkci setteru vlastnosti |

### Návratová hodnota

Hodnota vlastnosti před inkrementací

## Viz také

* jmenný prostor [System](../)
* knihovna [Aspose.Slides](../../)