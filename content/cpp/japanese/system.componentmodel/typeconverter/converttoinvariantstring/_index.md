---
title: ConvertToInvariantString()
second_title: Aspose.Slides for C++ APIリファレンス
description: オブジェクトを不変文字列に変換します。
type: docs
weight: 66
url: /ja/system.componentmodel/typeconverter/converttoinvariantstring/
---
## TypeConverter::ConvertToInvariantString(const System::SharedPtr\<System::Object\>\&) method

オブジェクトを不変文字列に変換します。

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToInvariantString(const System::SharedPtr<System::Object> &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) を変換します。 |

### 戻り値

変換されたオブジェクト。

## TypeConverter::ConvertToInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) method

オブジェクトを不変文字列に変換します。

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 変換コンテキスト情報。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) を変換します。 |

### 戻り値

変換されたオブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [TypeConverter](../)
* クラス [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 名前空間 [System::ComponentModel](../../)
* ライブラリ [Aspose.Slides](../../../)