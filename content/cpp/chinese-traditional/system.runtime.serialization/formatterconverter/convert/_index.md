---
title: Convert()
second_title: Aspose.Slides for C++ API 參考文件
description: "將值轉換為給定的 System::TypeInfo。"
type: docs
weight: 1
url: /zh-hant/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method

將值轉換為給定的 [System::TypeInfo](../../../system/typeinfo/)。

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要轉換的物件。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要將 value 轉換成的 [System::TypeInfo](../../../system/typeinfo/)。 |

### 傳回值

已轉換的值。

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method

將值轉換為給定的 [System::TypeCode](../../../system/typecode/)。

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要轉換的物件。 |
| typeCode | [TypeCode](../../../system/typecode/) | 要將 value 轉換成的 [System::TypeCode](../../../system/typecode/)。 |

### 傳回值

已轉換的值。

## 另請參閱

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)