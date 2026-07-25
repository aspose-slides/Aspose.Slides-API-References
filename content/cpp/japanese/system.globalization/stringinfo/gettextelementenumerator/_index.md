---
title: GetTextElementEnumerator()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列の文字を列挙する列挙子を作成します。
type: docs
weight: 118
url: /ja/system.globalization/stringinfo/gettextelementenumerator/
---
## StringInfo::GetTextElementEnumerator(const String\&) メソッド

文字列の文字を列挙する列挙子を作成します。

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) を列挙する対象。 |

### 戻り値

新しく作成された列挙子。

## StringInfo::GetTextElementEnumerator(const String\&, int) メソッド

指定したインデックスから開始して、文字列の文字を列挙する列挙子を作成します。

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) を列挙する対象。 |
| index | int | 開始インデックス。 |

### 戻り値

新しく作成された列挙子。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [TextElementEnumerator](../../textelementenumerator/)
* クラス [String](../../../system/string/)
* クラス [StringInfo](../)
* 名前空間 [System::Globalization](../../)
* Library [Aspose.Slides](../../../)