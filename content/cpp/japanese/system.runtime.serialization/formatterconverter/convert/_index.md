---
title: Convert()
second_title: Aspose.Slides for C++ API リファレンス
description: "指定された System::TypeInfo に値を変換します。"
type: docs
weight: 1
url: /ja/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) メソッド

指定された [System::TypeInfo](../../../system/typeinfo/) に値を変換します。

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 変換対象のオブジェクト。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | value が変換される [System::TypeInfo](../../../system/typeinfo/)。 |

### 戻り値

変換された値。

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) メソッド

指定された [System::TypeCode](../../../system/typecode/) に値を変換します。

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 変換対象のオブジェクト。 |
| typeCode | [TypeCode](../../../system/typecode/) | value が変換される [System::TypeCode](../../../system/typecode/)。 |

### 戻り値

変換された値。

## 参照

* 列挙体 [TypeCode](../../../system/typecode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [FormatterConverter](../)
* 名前空間 [System::Runtime::Serialization](../../)
* ライブラリ [Aspose.Slides](../../../)