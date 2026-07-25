---
title: ToDecimal()
second_title: Aspose.Slides for C++ API リファレンス
description: "このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して、同等の System::Decimal 数に変換します。"
type: docs
weight: 170
url: /ja/system/iconvertible/todecimal/
---
## IConvertible::ToDecimal(System::SharedPtr\<System::IFormatProvider\>) メソッド

このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して、同等の [System::Decimal](../../decimal/) 数に変換します。

```cpp
virtual System::Decimal System::IConvertible::ToDecimal(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) インターフェイスの実装で、カルチャ固有の書式情報を提供します。 |

### 戻り値

このインスタンスの値に相当する [System::Decimal](../../decimal/) の数です。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [Decimal](../../decimal/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [IConvertible](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)