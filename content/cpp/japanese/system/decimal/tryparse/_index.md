---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 数値の文字列表現を含む指定された文字列を、同等の Decimal 値に変換します。
type: docs
weight: 482
url: /ja/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) メソッド

数値の文字列表現を含む指定された文字列を、同等の [Decimal](../) 値に変換します。

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| result | [Decimal](../)\& | 変換結果が格納される [Decimal](../) 変数への参照 |

### 戻り値

変換が成功した場合は True、そうでない場合は false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) メソッド

数値の文字列表現を含む指定された文字列を、提供された書式情報と数値スタイルを使用して同等の [Decimal](../) 値に変換します。

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体のビット単位の組み合わせで、文字列の数値表現に許可されるスタイルを指定 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列の書式情報を含むオブジェクトへのポインタ |
| result | [Decimal](../)\& | 出力引数; 変換結果が格納される |

### 戻り値

変換が成功した場合は True、そうでない場合は false

## 参照

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)