---
title: Convert()
second_title: Aspose.Slides for C++ API 參考
description: RTTI 資訊。
type: docs
weight: 1
url: /zh-hant/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) 方法

RTTI 資訊。

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要轉換的物件。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要將值轉換為的 [System::TypeInfo](../../../system/typeinfo/)。 |

### 回傳值

已轉換的值。

## 備註

將值轉換為給定的 [System::TypeInfo](../../../system/typeinfo/)。

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) 方法

將值轉換為給定的 [System::TypeCode](../../../system/typecode/)。

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要轉換的物件。 |
| typeCode | [TypeCode](../../../system/typecode/) | 要將值轉換為的 [System::TypeCode](../../../system/typecode/)。 |

### 回傳值

已轉換的值。

## 另見

* 列舉 [TypeCode](../../../system/typecode/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [IFormatterConverter](../)
* 命名空間 [System::Runtime::Serialization](../../)
* 函式庫 [Aspose.Slides](../../../)