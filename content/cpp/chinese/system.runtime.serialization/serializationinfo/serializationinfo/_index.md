---
title: SerializationInfo()
second_title: Aspose.Slides for C++ API 参考
description: RTTI 信息。
type: docs
weight: 1
url: /zh/system.runtime.serialization/serializationinfo/serializationinfo/
---
## SerializationInfo::SerializationInfo(const System::TypeInfo\&, const System::SharedPtr\<IFormatterConverter\>\&) constructor


RTTI 信息。

```cpp
System::Runtime::Serialization::SerializationInfo::SerializationInfo(const System::TypeInfo &type, const System::SharedPtr<IFormatterConverter> &converter)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [System::TypeInfo](../../../system/typeinfo/)\& | 要序列化的对象的 [System::TypeInfo](../../../system/typeinfo/)。 |
| converter | const [System::SharedPtr](../../../system/sharedptr/)\<[IFormatterConverter](../../iformatterconverter/)\>\& | 反序列化期间使用的 [IFormatterConverter](../../iformatterconverter/)。 |
## 备注

创建 [SerializationInfo](../) 类的新实例。 
## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../../iformatterconverter/)
* Class [SerializationInfo](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)