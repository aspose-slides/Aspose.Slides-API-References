---
title: ConvertTo()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトを特定の型に変換します。
type: docs
weight: 14
url: /ja/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) メソッド

オブジェクトを特定の型に変換します。

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 変換コンテキスト情報 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | オブジェクトを変換するときに使用するカルチャ |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 変換するオブジェクト |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 変換先の型 |

### 戻り値

変換されたオブジェクト。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [ImageConverter](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)