---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定のアイテムの最初のインデックスを取得します。
type: docs
weight: 222
url: /ja/system.collections.generic/list/indexof/
---
## List::IndexOf(const T&) const メソッド

特定のアイテムの最初のインデックスを取得します。

```cpp
int System::Collections::Generic::List<T>::IndexOf(const T &item) const override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | 検索対象のアイテム。 |

### 戻り値

[Index](../../../system/index/) は、指定されたアイテムが最初に出現したインデックス、または見つからない場合は -1 です。

## List::IndexOf(const T&, int) const メソッド

リスト内の特定のアイテムを検索します。

```cpp
int System::Collections::Generic::List<T>::IndexOf(const T &item, int index) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | 検索対象のアイテム。 |
| index | int | [Index](../../../system/index/) は検索を開始するインデックスです。 |

### 戻り値

[Index](../../../system/index/) は、指定されたアイテムが最初に出現したインデックス、または見つからない場合は -1 です。

## 参照

* クラス [List](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)