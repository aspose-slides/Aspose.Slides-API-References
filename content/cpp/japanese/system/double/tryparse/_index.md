---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現）を、同等の倍精度浮動小数点値に変換します。
type: docs
weight: 14
url: /ja/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) メソッド

指定された文字列（数値の文字列表現）を、同等の倍精度浮動小数点値に変換します。

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| result | **double**\& | 変換結果が格納される倍精度浮動小数点変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false です。

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) メソッド

提供された書式情報と数値スタイルを使用して、指定された文字列（数値の文字列表現）を同等の倍精度浮動小数点値に変換します。

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 数値の文字列表現に許可されるスタイルを指定する NumberStyles 列挙体の値をビット単位で組み合わせたもの。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を保持するオブジェクトへのポインタ。 |
| result | **double**\& | 変換結果が格納される倍精度浮動小数点変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false です。

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) メソッド


```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) メソッド


```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) メソッド


```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## 参照

* 列挙型 [NumberStyles](../../../system.globalization/numberstyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 構造体 [Double](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)