---
title: setter_increment_wrap()
second_title: Aspose.Slides for C++ API Reference
description: Translator translates C#'s increment expressions targeting class' property that has setter and getter defined, into invocation of this function.
type: docs
weight: 1860
url: /cpp/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) function


Translator translates C#'s increment expressions targeting class' property that has setter and getter defined, into invocation of this function.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the property |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Function pointer pointing to the property's getter free function |
| pSetter | void(*)(T) | Function pointer pointing to the property's setter free function |

### Return Value

The incremented value of the property

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function


Translator translates C#'s increment expressions targeting class' property that has setter and getter defined, into invocation of this function.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the property |
| Host | - class of instance to be modified |
| HostGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | A pointer to an object whose property is to be incremented |
| pGetter | T(HostGet::*)() | Function pointer pointing to the property's getter method |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter method |

### Return Value

The incremented value of the property

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)