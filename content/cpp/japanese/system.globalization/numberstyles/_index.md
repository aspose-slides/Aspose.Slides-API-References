---
title: NumberStyles
second_title: Aspose.Slides for C++ API リファレンス
description: 解析時に許可される数値スタイルです。
type: docs
weight: 495
url: /ja/system.globalization/numberstyles/
---
## NumberStyles 列挙型

解析時に許可される数値スタイルです。

```cpp
enum class NumberStyles : int32_t
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | 数字以外の記号は許可されません。 |
| AllowLeadingWhite | 1 | 先頭の空白文字を許可します。 |
| AllowTrailingWhite | 2 | 末尾の空白文字を許可します。 |
| AllowLeadingSign | 4 | 先頭の符号を許可します。 |
| Integer | n/a | デフォルトの整数書式です。 |
| AllowTrailingSign | 8 | 末尾の符号を許可します。 |
| AllowParentheses | 16 | 負の値に丸括弧を許可します。 |
| AllowDecimalPoint | 32 | 小数点を許可します。 |
| AllowThousands | 64 | 桁区切り文字を許可します。 |
| Number | n/a | デフォルトの複合数形式です。 |
| AllowExponent | 128 | 指数符号を許可します。 |
| Float | n/a | デフォルトの浮動小数点数形式です。 |
| AllowCurrencySymbol | 256 | 通貨記号を許可します。 |
| Currency | n/a | デフォルトの通貨書式です。 |
| Any | n/a | 任意の書式指定子を許可します。 |
| AllowHexSpecifier | 512 | 十六進数を許可します。 |
| HexNumber | n/a | デフォルトの十六進数書式です。 |

## 参照

* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)