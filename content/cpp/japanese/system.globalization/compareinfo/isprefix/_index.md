---
title: IsPrefix()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定された比較オプションを使用して、指定された文字列が指定されたプレフィックスで始まるかどうかを確認します。
type: docs
weight: 105
url: /ja/system.globalization/compareinfo/isprefix/
---
## CompareInfo::IsPrefix(const String\&, const String\&, CompareOptions) const メソッド

指定された比較オプションを使用して、指定された文字列が指定されたプレフィックスで始まるかどうかを確認します。

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix, CompareOptions options) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | ソース文字列。 |
| prefix | const [String](../../../system/string/)\& | プレフィックス文字列。 |
| options | [CompareOptions](../../compareoptions/) | 比較オプション。 |

### 戻り値

文字列がプレフィックスで始まる場合は true、そうでなければ false。

## CompareInfo::IsPrefix(const String\&, const String\&) const メソッド

指定された文字列が指定されたプレフィックスで始まるかどうかを確認します。

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | ソース文字列。 |
| prefix | const [String](../../../system/string/)\& | プレフィックス文字列。 |

### 戻り値

文字列がプレフィックスで始まる場合は true、そうでなければ false。

## 参照

* 列挙体 [CompareOptions](../../compareoptions/)
* クラス [String](../../../system/string/)
* クラス [CompareInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)