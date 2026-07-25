---
title: ConvertFrom()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトを変換します。
type: docs
weight: 14
url: /ja/system.drawing/imageformatconverter/convertfrom/
---
## ImageFormatConverter::ConvertFrom(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&) メソッド


オブジェクトを変換します。

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertFrom(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 変換コンテキスト情報。 |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | オブジェクトを変換する際に使用するカルチャー。 |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) 変換対象。 |

### 戻り値

変換されたオブジェクト。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [ImageFormatConverter](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)