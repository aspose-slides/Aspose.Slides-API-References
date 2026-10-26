---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列を bool 型の値に変換します。
type: docs
weight: 14
url: /ja/system/boolean/tryparse/
---
## Boolean::TryParse(const String\&, bool\&) メソッド


Converts the specified string to a value of bool type.

```cpp
static bool System::Boolean::TryParse(const String &value, bool &result)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| result | **bool**\& | 変換結果を格納する bool 変数への参照。指定された文字列が "True" と等しい場合は true、"False" と等しい場合は false が格納されます。 |

### 戻り値

指定された文字列が "True" または "False" のいずれかと等しい場合は True、そうでなければ false。

## 参照

* クラス [String](../../string/)
* クラス [Boolean](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)