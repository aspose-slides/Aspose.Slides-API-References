---
title: GetSortKey()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された比較オプションを使用して、指定された文字列の SortKey オブジェクトを取得します。
type: docs
weight: 79
url: /ja/system.globalization/compareinfo/getsortkey/
---
## CompareInfo::GetSortKey(const String\&, CompareOptions) const method

指定された比較オプションを使用して、指定された文字列の [SortKey](../../sortkey/) オブジェクトを取得します。

```cpp
virtual SortKeyPtr System::Globalization::CompareInfo::GetSortKey(const String &value, CompareOptions options) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 入力文字列。 |
| options | [CompareOptions](../../compareoptions/) | 比較オプション。 |

### 戻り値

[SortKey](../../sortkey/) オブジェクト。

## CompareInfo::GetSortKey(const String\&) const method

指定された文字列の [SortKey](../../sortkey/) オブジェクトを取得します。

```cpp
virtual SortKeyPtr System::Globalization::CompareInfo::GetSortKey(const String &value) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 入力文字列。 |

### 戻り値

[SortKey](../../sortkey/) オブジェクト。

## 参照

* 列挙体 [CompareOptions](../../compareoptions/)
* 型定義 [SortKeyPtr](../../sortkeyptr/)
* クラス [String](../../../system/string/)
* クラス [CompareInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)