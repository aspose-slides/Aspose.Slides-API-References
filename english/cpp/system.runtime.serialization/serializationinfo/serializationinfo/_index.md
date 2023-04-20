---
title: SerializationInfo()
second_title: Aspose.Slides for C++ API Reference
description: RTTI information.
type: docs
weight: 1
url: /cpp/system.runtime.serialization/serializationinfo/serializationinfo/
---
## SerializationInfo::SerializationInfo(const System::TypeInfo\&, const System::SharedPtr\<IFormatterConverter\>\&) constructor


RTTI information.

```cpp
System::Runtime::Serialization::SerializationInfo::SerializationInfo(const System::TypeInfo &type, const System::SharedPtr<IFormatterConverter> &converter)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [System::TypeInfo](../../../system/typeinfo/)\& | The [System::TypeInfo](../../../system/typeinfo/) of the object to serialize. |
| converter | const [System::SharedPtr](../../../system/sharedptr/)\<[IFormatterConverter](../../iformatterconverter/)\>\& | The [IFormatterConverter](../../iformatterconverter/) used during deserialization. |
## Remarks


Creates a new instance of the [SerializationInfo](../) class. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../../iformatterconverter/)
* Class [SerializationInfo](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)