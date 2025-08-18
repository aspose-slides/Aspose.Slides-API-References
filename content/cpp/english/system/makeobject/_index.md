---
title: MakeObject()
second_title: Aspose.Slides for C++ API Reference
description: Creates object on heap and returns shared pointer to it.
type: docs
weight: 2627
url: /system/makeobject/
---
## System::MakeObject(Args\&&...) function


Creates object on heap and returns shared pointer to it.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Class to instantiate. |
| Args | Constructor arguments' types. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Constructor arguments. |

### Return Value

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## System::MakeObject(Args\&&...) function


Creates object on heap and returns shared pointer to it.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [SmartPtr](../smartptr/) to class to instantiate. |
| Args | Constructor arguments' types. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Constructor arguments. |

### Return Value

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## See Also

* Class [SmartPtr](../smartptr/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)