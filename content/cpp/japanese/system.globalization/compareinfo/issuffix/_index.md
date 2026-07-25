---
title: IsSuffix()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された比較オプションを使用して、指定された文字列が指定されたサフィックスで終わるかどうかを確認します。
type: docs
weight: 118
url: /ja/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const メソッド


指定されたStringが、指定されたsuffixで終わっているかどうかを、指定されたCompareOptionsを使用して確認します。

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | ソース文字列。 |
| suffix | const [String](../../../system/string/)\& | サフィックス文字列。 |
| options | [CompareOptions](../../compareoptions/) | 比較オプション。 |

### 戻り値

文字列がsuffixで終わる場合はTrue、そうでない場合はFalse。

## CompareInfo::IsSuffix(const String\&, const String\&) const メソッド


指定されたStringが、指定されたsuffixで終わっているかどうかを確認します。

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | ソース文字列。 |
| suffix | const [String](../../../system/string/)\& | サフィックス文字列。 |

### 戻り値

文字列がsuffixで終わる場合はTrue、そうでない場合はFalse。

## 関連項目

* 列挙 [CompareOptions](../../compareoptions/)
* クラス [String](../../../system/string/)
* クラス [CompareInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)