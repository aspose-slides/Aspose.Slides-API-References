---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現）を 16 ビット符号付き整数に変換します。
type: docs
weight: 14
url: /ja/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) メソッド


指定された文字列（数値の文字列表現）を 16 ビット符号付き整数に変換します。

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| result | **int16_t**\& | 変換結果が格納される 16 ビット符号付き整数変数への参照。 |

### 戻り値

変換が成功した場合は True、そうでない場合は false。

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) メソッド


指定された文字列（数値の文字列表現）を、提供された書式情報と数値スタイルを使用して 16 ビット符号付き整数に変換します。

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体の値のビット単位の組み合わせで、数値の文字列表現に許可されるスタイルを指定します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |
| result | **int16_t**\& | 変換結果が格納される 16 ビット符号付き整数変数への参照。 |

### 戻り値

変換が成功した場合は True、そうでない場合は false。

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) メソッド




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) メソッド




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) メソッド




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## 参照

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Int16](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)