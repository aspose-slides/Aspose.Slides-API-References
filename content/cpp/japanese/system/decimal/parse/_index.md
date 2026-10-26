---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 10進数の文字列表現を Decimal クラスの同等のインスタンスに変換します。
type: docs
weight: 469
url: /ja/system/decimal/parse/
---
## Decimal::Parse(const String\&) メソッド

10進数の文字列表現を [Decimal](../) クラスの同等のインスタンスに変換します。

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 数値の文字列表現 |

### 戻り値

指定された文字列が表す値と等価な値を表す [Decimal](../) クラスの新しいインスタンス。

## Decimal::Parse(const String\&, Globalization::NumberStyles) メソッド

指定されたスタイルを使用して、10進数の文字列表現を [Decimal](../) クラスの同等のインスタンスに変換します。

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換する10進数値の文字列表現 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | **s** に関する追加情報、**s** に存在する可能性のあるスタイル要素、または **s** から [Decimal](../) オブジェクトへの変換に関する情報を提供する列挙値のビット単位の組み合わせ |

### 戻り値

指定された文字列が表す値と等価な値を表す [Decimal](../) クラスの新しいインスタンス。

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたフォーマットプロバイダーを使用して、10進数の文字列表現を [Decimal](../) クラスの同等のインスタンスに変換します。

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換する10進数値の文字列表現 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | フォーマットプロバイダー |

### 戻り値

指定された文字列が表す値と等価な値を表す [Decimal](../) クラスの新しいインスタンス。

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたスタイルとフォーマットプロバイダーを使用して、10進数の文字列表現を [Decimal](../) クラスの同等のインスタンスに変換します。

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換する10進数値の文字列表現 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | **s** に関する追加情報、**s** に存在する可能性のあるスタイル要素、または **s** から [Decimal](../) オブジェクトへの変換に関する情報を提供する列挙値のビット単位の組み合わせ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | フォーマットプロバイダー |

### 戻り値

指定された文字列が表す値と等価な値を表す [Decimal](../) クラスの新しいインスタンス。

## 参照

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)