---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: "指定されたカルチャ固有の書式情報を使用して、このインスタンスの値を同等の System::String に変換します。"
type: docs
weight: 196
url: /ja/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) メソッド

このインスタンスの値を、指定されたカルチャ固有の書式情報を使用して、同等の[System::String](../../string/)に変換します。

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) インターフェイスの実装で、カルチャ固有の書式情報を提供します。 |

### 戻り値

このインスタンスの値と同等の[System::String](../../string/) インスタンスです。

## IConvertible::ToString() const メソッド

C# の [Object.ToString()](../../object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。

```cpp
virtual String System::Object::ToString() const
```

### 戻り値

[String](../../string/) の表現は、最終クラスによって提供されます。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [IConvertible](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)