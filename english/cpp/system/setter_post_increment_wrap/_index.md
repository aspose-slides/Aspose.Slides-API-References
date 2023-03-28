---
title: setter_post_increment_wrap()
second_title: Aspose.Slides for C++ API Reference
description: Translator translates C#'s post-increment expressions targeting class' property that has setter and getter defined, into invocation of this function.
type: docs
weight: 2445
url: /cpp/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) function


Translator translates C#'s post-increment expressions targeting class' property that has setter and getter defined, into invocation of this function.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
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

The value of the property before incrementing

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function


Translator translates C#'s post-increment expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for non-const getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the property. |
| Host | - class of instance to be modified |
| HostGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostGet::*)() | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### Return Value

The value of the property before incrementing

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function


Translator translates C#'s post-increment expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the property. |
| Host | - class of instance to be modified |
| HostConstGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostConstGet::*)() const | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### Return Value

The value of the property before incrementing

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
