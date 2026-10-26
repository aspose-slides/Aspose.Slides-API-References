---
title: IsSortable()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字が並べ替え可能かどうかを確認します。
type: docs
weight: 196
url: /ja/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) メソッド


指定された文字が並べ替え可能かどうかを確認します。

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | char16_t | Unicode 文字。 |

### 戻り値

**ch** が並べ替え可能な場合は true、そうでない場合は false。

## CompareInfo::IsSortable(const String\&) メソッド


指定された文字列が並べ替え可能かどうかを確認します。

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 文字列。 |

### 戻り値

**text** が空でなく、かつ **text** 内のすべての文字が並べ替え可能な場合は true、そうでない場合は false。

## 参照

* クラス [CompareInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)