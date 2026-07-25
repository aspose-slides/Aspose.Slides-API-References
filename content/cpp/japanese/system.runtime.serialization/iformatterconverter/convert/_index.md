---
title: Convert()
second_title: Aspose.Slides for C++ API リファレンス
description: RTTI 情報。
type: docs
weight: 1
url: /ja/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) メソッド


RTTI 情報。

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Arguments

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 変換対象のオブジェクト。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | value が変換される [System::TypeInfo](../../../system/typeinfo/)。 |

### Return Value

変換後の値。

## 備考


指定された [System::TypeInfo](../../../system/typeinfo/) に値を変換します。

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) メソッド


指定された [System::TypeCode](../../../system/typecode/) に値を変換します。

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Arguments

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 変換対象のオブジェクト。 |
| typeCode | [TypeCode](../../../system/typecode/) | value が変換される [System::TypeCode](../../../system/typecode/)。 |

### Return Value

変換後の値。

## 参照

* 列挙型 [TypeCode](../../../system/typecode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [IFormatterConverter](../)
* 名前空間 [System::Runtime::Serialization](../../)
* ライブラリ [Aspose.Slides](../../../)