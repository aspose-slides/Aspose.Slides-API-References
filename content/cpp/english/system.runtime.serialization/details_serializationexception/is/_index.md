---
title: Is()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 27
url: /system.runtime.serialization/details_serializationexception/is/
---
## Details_SerializationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) structure describing the type to test current object against. |

### Return Value

True if object is of tagged type or its subclass, false otherwise.
## Remarks


Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 
## See Also

* Class [TypeInfo](../../../system/typeinfo/)
* Class [Details_SerializationException](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)