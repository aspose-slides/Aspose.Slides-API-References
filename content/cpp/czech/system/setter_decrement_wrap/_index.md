---
title: setter_decrement_wrap()
second_title: Aspose.Slides pro C++ API Reference
description: Překladač převádí predekrementační výrazy jazyka C#, které cílí na vlastnost třídy s definovaným setterem a getterem, na volání této funkce.
type: docs
weight: 2861
url: /cs/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) function


Překladač převádí predekrementační výrazy jazyka C# zaměřené na vlastnost třídy, která má definován setter i getter, na volání této funkce.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Typ vlastnosti |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Ukazatel na funkci ukazující na getter volné funkce vlastnosti |
| pSetter | void(*)(T) | Ukazatel na funkci ukazující na setter volné funkce vlastnosti |

### Return Value

Hodnota vlastnosti před inkrementací

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function


Překladač převádí predekrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definován setter i getter, na volání této funkce (přetížení pro ne-konstantní getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Typ vlastnosti. |
| Host | - třída instance, která má být upravena |
| HostGet | - Host samotný, nebo jeho základní typ, kde je definován getter vlastnosti |
| HostSet | - Host samotný, nebo jeho základní typ, kde je definován setter vlastnosti |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance, pro kterou se volají gettery a settery. |
| pGetter | T(HostGet::*)() | Ukazatel na funkci ukazující na getter funkci vlastnosti |
| pSetter | void(HostSet::*)(T) | Ukazatel na funkci ukazující na setter funkci vlastnosti |

### Return Value

Hodnota vlastnosti před inkrementací

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function


Překladač převádí predekrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definován setter i getter, na volání této funkce (přetížení pro konstantní getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Typ vlastnosti. |
| Host | - třída instance, která má být upravena |
| HostConstGet | - Host samotný, nebo jeho základní typ, kde je definován getter vlastnosti |
| HostSet | - Host samotný, nebo jeho základní typ, kde je definován setter vlastnosti |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance, pro kterou se volají gettery a settery. |
| pGetter | T(HostConstGet::*)() const | Ukazatel na funkci ukazující na getter funkci vlastnosti |
| pSetter | void(HostSet::*)(T) | Ukazatel na funkci ukazující na setter funkci vlastnosti |

### Return Value

Hodnota vlastnosti před inkrementací

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)