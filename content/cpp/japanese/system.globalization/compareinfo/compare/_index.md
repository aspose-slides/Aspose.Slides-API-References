---
title: Compare()
second_title: Aspose.Slides の C++ API リファレンス
description: 文字列を比較します。実装されていません。
type: docs
weight: 66
url: /ja/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method

文字列を比較します。実装されていません。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 左側文字列。 |
| string2 | const [String](../../../system/string/)\& | 右側文字列。 |

### 戻り値

LHS文字列がRHS文字列より前にある場合は負の値、等しい場合はゼロ、そうでない場合は正の値を返します。

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method

文字列を比較します。Ordinal と OrdinalIgnoreCase モードのみがサポートされています。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | 左側文字列。 |
| b | const [String](../../../system/string/)\& | 右側文字列。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較タイプ。 |

### 戻り値

LHS文字列がRHS文字列より前にある場合は負の値、等しい場合はゼロ、そうでない場合は正の値を返します。

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method

文字列の一部と別の文字列の一部を比較します。実装されていません。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 最初の文字列。 |
| offset1 | int | **string1** の文字の開始インデックス。 |
| length1 | int | 比較する **string1** の文字数。 |
| string2 | const [String](../../../system/string/)\& | 2番目の文字列。 |
| offset2 | int | **string2** の文字の開始インデックス。 |
| length2 | int | 比較する **string2** の文字数。 |

### 戻り値

最初の文字列セクションが2番目の文字列セクションより前にある場合は負の値、等しい場合はゼロ、そうでない場合は正の値を返します。

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method

文字列比較メソッドを使用して、文字列の末尾セクションと別の文字列の末尾セクションを比較します。実装されていません。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 最初の文字列。 |
| offset1 | int | **string1** の文字の開始インデックス。 |
| string2 | const [String](../../../system/string/)\& | 2番目の文字列。 |
| offset2 | int | **string2** の文字の開始インデックス。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較オプション。 |

### 戻り値

最初の文字列セクションが2番目の文字列セクションより前にある場合は負の値、等しい場合はゼロ、そうでない場合は正の値を返します。

## CompareInfo::Compare(const String\&, int, const String\&, int) const method

文字列の末尾セクションと別の文字列の末尾セクションを比較します。実装されていません。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 最初の文字列。 |
| offset1 | int | **string1** の文字の開始インデックス。 |
| string2 | const [String](../../../system/string/)\& | 2番目の文字列。 |
| offset2 | int | **string2** の文字の開始インデックス。 |

### 戻り値

最初の文字列セクションが2番目の文字列セクションより前にある場合は負の値、等しい場合はゼロ、そうでない場合は正の値を返します。

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method

文字列比較メソッドを使用して、文字列の一部と別の文字列の一部を比較します。実装されていません。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 最初の文字列。 |
| offset1 | int | **string1** の文字の開始インデックス。 |
| length1 | int | 比較する **string1** の文字数。 |
| string2 | const [String](../../../system/string/)\& | 2番目の文字列。 |
| offset2 | int | **string2** の文字の開始インデックス。 |
| length2 | int | 比較する **string2** の文字数。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較オプション。 |

### 戻り値

最初の文字列セクションが2番目の文字列セクションより前にある場合は負の値、等しい場合はゼロ、そうでない場合は正の値を返します。

## 参照

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)