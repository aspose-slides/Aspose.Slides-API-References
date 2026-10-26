---
title: ConvertFrom()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトを変換します。
type: docs
weight: 1
url: /ja/system.drawing/fontconverter/convertfrom/
---
## FontConverter::ConvertFrom(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) メソッド

オブジェクトを変換します。

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertFrom(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 変換コンテキスト情報。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | オブジェクトを変換する際に使用するカルチャー。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 変換対象のオブジェクト。 |

### 戻り値

変換されたオブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [FontConverter](../)
* 名前空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)