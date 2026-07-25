---
title: ConvertTo()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトを特定の型に変換します。
type: docs
weight: 27
url: /ja/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) method

オブジェクトを特定の型に変換します。

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 変換コンテキスト情報。 |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | オブジェクト変換時に使用するカルチャ。 |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) 変換対象。 |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | 変換先の型。 |

### 戻り値

変換されたオブジェクト。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [ImageFormatConverter](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)