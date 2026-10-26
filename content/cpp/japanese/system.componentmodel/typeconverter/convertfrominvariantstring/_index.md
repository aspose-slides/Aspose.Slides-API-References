---
title: ConvertFromInvariantString()
second_title: Aspose.Slides for C++ API リファレンス
description: 不変文字列をオブジェクトに変換します。
type: docs
weight: 27
url: /ja/system.componentmodel/typeconverter/convertfrominvariantstring/
---
## TypeConverter::ConvertFromInvariantString(const System::String\&) メソッド


不変文字列をオブジェクトに変換します。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::String &text)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 変換する値。 |

### 戻り値

変換されたオブジェクト。

## TypeConverter::ConvertFromInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) メソッド


不変文字列をオブジェクトに変換します。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 変換コンテキスト情報。 |
| text | const [System::String](../../../system/string/)\& | 変換する値。 |

### 戻り値

変換されたオブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [String](../../../system/string/)
* クラス [TypeConverter](../)
* クラス [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 名前空間 [System::ComponentModel](../../)
* ライブラリ [Aspose.Slides](../../../)