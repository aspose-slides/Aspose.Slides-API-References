---
title: ToType()
second_title: Aspose.Slides for C++ API リファレンス
description: "このインスタンスの値を、指定された System::Type の System::Object に変換し、指定されたカルチャ固有の書式設定情報を使用して等価な値にします。"
type: docs
weight: 209
url: /ja/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) method

このインスタンスの値を、指定された System::Type の [System::Object](../../object/) に変換し、指定されたカルチャ固有の書式設定情報を使用して等価な値を持たせます。

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | このインスタンスの値が変換される System::Type。 |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) インターフェイス実装で、カルチャ固有の書式設定情報を提供します。 |

### 戻り値

[System::Object](../../object/) のインスタンスで、型は conversionType で、値はこのインスタンスの値と等価です。

## 関連項目

* Typedef [SharedPtr](../../sharedptr/)
* クラス [Object](../../object/)
* クラス [TypeInfo](../../typeinfo/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [IConvertible](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)