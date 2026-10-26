---
title: ToChar()
second_title: Aspose.Slides for C++ API リファレンス
description: このインスタンスの値を、指定されたカルチャ固有の書式設定情報を使用して、等価の Unicode 文字に変換します。
type: docs
weight: 27
url: /ja/system/iconvertible/tochar/
---
## IConvertible::ToChar(System::SharedPtr\<System::IFormatProvider\>) メソッド


このインスタンスの値を、指定されたカルチャ固有の書式設定情報を使用して、等価の Unicode 文字に変換します。

```cpp
virtual char_t System::IConvertible::ToChar(System::SharedPtr<System::IFormatProvider> provider)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) インターフェイス実装で、カルチャ固有の書式設定情報を提供します。 |

### 戻り値

このインスタンスの値に相当する Unicode 文字。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [IConvertible](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)