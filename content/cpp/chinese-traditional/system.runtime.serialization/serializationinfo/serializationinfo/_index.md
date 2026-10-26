---
title: SerializationInfo()
second_title: Aspose.Slides C++ API 參考
description: RTTI 資訊。
type: docs
weight: 1
url: /zh-hant/system.runtime.serialization/serializationinfo/serializationinfo/
---
## SerializationInfo::SerializationInfo(const System::TypeInfo&, const System::SharedPtr\<IFormatterConverter\>&) 建構函式


RTTI 資訊。

```cpp
System::Runtime::Serialization::SerializationInfo::SerializationInfo(const System::TypeInfo &type, const System::SharedPtr<IFormatterConverter> &converter)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | const [System::TypeInfo](../../../system/typeinfo/)\& | 要序列化之物件的 [System::TypeInfo](../../../system/typeinfo/)。 |
| converter | const [System::SharedPtr](../../../system/sharedptr/)\<[IFormatterConverter](../../iformatterconverter/)\>\& | 反序列化期間使用的 [IFormatterConverter](../../iformatterconverter/)。 |

## 備註

建立 [SerializationInfo](../) 類別的新實例。 

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../../iformatterconverter/)
* Class [SerializationInfo](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)