---
title: StaticCastArray()
second_title: Aspose.Slides for C++ API Reference
description: Performs casting of elements of the specified array to different type. Override for cases then From is SmartPtr obj.
type: docs
weight: 2666
url: /system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


Performs casting of elements of the specified array to different type. Override for cases then From is [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### Return Value

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

Deprecated
:   Added for backward compatibility. Use ExplicitCast instead.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


Performs casting of elements of the specified array to different type. Override for cases then From is Boxable and To is [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### Return Value

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

Deprecated
:   Added for backward compatibility. Use ExplicitCast instead.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Class [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)