---
title: ToDateTime()
second_title: Aspose.Slides for C++ API リファレンス
description: "このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して、同等の System::DateTime に変換します。"
type: docs
weight: 183
url: /ja/system/iconvertible/todatetime/
---
## IConvertible::ToDateTime(System::SharedPtr\<System::IFormatProvider\>) メソッド

このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して、同等の[System::DateTime](../../datetime/)に変換します。

```cpp
virtual System::DateTime System::IConvertible::ToDateTime(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) インターフェイスの実装で、カルチャ固有の書式情報を提供します。 |

### 戻り値

このインスタンスの値に相当する[System::DateTime](../../datetime/)インスタンスです。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [DateTime](../../datetime/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [IConvertible](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)