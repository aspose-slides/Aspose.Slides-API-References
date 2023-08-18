---
title: Cast()
second_title: Aspose.Slides for C++ API Reference
description: Casts pointer to its type itself.
type: docs
weight: 287
url: /system/smartptr/cast/
---
## SmartPtr::Cast() const method


Casts pointer to its type itself.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Return Value

Pointer of changed type which is always in shared mode.

## SmartPtr::Cast() const method


Casts pointer to base type using static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Return Value

Pointer of changed type which is always in shared mode.

## SmartPtr::Cast() const method


Casts pointer to derived type dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Return Value

Pointer of changed type which is always in shared mode. Throws InvalidCastException if no conversion available.

## SmartPtr::Cast() const method


Casts pointer to derived type dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Return Value

Pointer of changed type which is always in shared mode. Returns nullptr if no conversion available.

## See Also

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)