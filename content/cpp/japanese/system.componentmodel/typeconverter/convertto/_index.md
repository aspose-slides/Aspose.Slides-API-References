---
title: ConvertTo()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトを特定の型に変換します。
type: docs
weight: 53
url: /ja/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) メソッド

オブジェクトを特定の型に変換します。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) を変換する対象。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 変換先の型。 |

### 戻り値

変換されたオブジェクト。

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) メソッド

オブジェクトを特定の型に変換します。

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 変換コンテキスト情報。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | オブジェクト変換時に使用するカルチャー。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) を変換する対象。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 変換先の型。 |

### 戻り値

変換されたオブジェクト。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [TypeConverter](../)
* クラス [ITypeDescriptorContext](../../itypedescriptorcontext/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* 名前空間 [System::ComponentModel](../../)
* ライブラリ [Aspose.Slides](../../../)