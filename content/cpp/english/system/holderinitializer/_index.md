---
title: HolderInitializer
second_title: Aspose.Slides for C++ API Reference
description: This class used to get persistent reference to the object instance, whatever it is lvalue or rvalue. To ubtain such reference, use 'HoldIfTemporary' method, that has there overloads. Two of them take rvalue as a parameter, and just return the reference to it. The third one, in opposite, takes lvalue as a parameter, makes a pointer copy, then return reference to that copy. Also, class has 'Hold' method to hold passed value unconditionally (used to copy values of a local on-stack variables or it's child references)
type: docs
weight: 1600
url: /system/holderinitializer/
---
## HolderInitializer struct


This class used to get persistent reference to the object instance, whatever it is lvalue or rvalue. To ubtain such reference, use 'HoldIfTemporary' method, that has there overloads. Two of them take rvalue as a parameter, and just return the reference to it. The third one, in opposite, takes lvalue as a parameter, makes a pointer copy, then return reference to that copy. Also, class has 'Hold' method to hold passed value unconditionally (used to copy values of a local on-stack variables or it's child references)

```cpp
template<typename T,bool>class HolderInitializer
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the object to hold to. |
| R | True, if T is a reference type ([SmartPtr](../smartptr/) specialization or [System::String](../string/) type), and temporary references holding is actually required, false - otherwise. |
## Methods

| Method | Description |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Copies passed lvalue to holder, then return the holder reference Caller should use this method to hold passed value unconditionally. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Initializes holder reference with passed one. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Returns reference to rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Returns reference to rvalue (non-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Copies passed lvalue to holder, then return the holder reference. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)