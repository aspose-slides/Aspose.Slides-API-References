---
title: SmartPtrInfo
second_title: Aspose.Slides for C++ API Reference
description: Service class to test and alter SmartPtr's contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use SmartPtr's basetype as it doesn't have any; instead, we use this 'info' class.
type: docs
weight: 1132
url: /cpp/system/smartptrinfo/
---
## SmartPtrInfo class


Service class to test and alter [SmartPtr](../smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](../smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class.

```cpp
class SmartPtrInfo
```

## Methods

| Method | Description |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Gets raw object referenced pointer points to. |
| [Object](../object/) * [getObject](./getobject/)() const | Gets object referenced pointer points to. |
| [Object](../object/) * [getOwned](./getowned/)() const | Gets object owned pointer. |
|  [operator bool](./operator_bool/)() const | Checks if info object points to non-null pointer. |
| **bool** [operator!](./operator_not/)() const | Checks if info object does not point to non-null pointer. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Allows to call methods of [Object](../object/) pointed by the referenced pointer. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Less-compares values of pointers referenced by two info objects. |
|  [SmartPtrInfo](./smartptrinfo/)() | Creates empty [SmartPtrInfo](./) object. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Creates [SmartPtrInfo](./) object with information on specific smart pointer. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
