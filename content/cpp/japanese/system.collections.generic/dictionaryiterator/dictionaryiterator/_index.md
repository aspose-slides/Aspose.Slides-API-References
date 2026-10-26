---
title: DictionaryIterator()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.collections.generic/dictionaryiterator/dictionaryiterator/
---
## DictionaryIterator::DictionaryIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) コンストラクタ

コンストラクタ。

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 保持するイテレータ。 |
| end | typename Dict::map_t::const_iterator\&& | コンテナの終端を指すイテレータ。 |

## DictionaryIterator::DictionaryIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) コンストラクタ

コンストラクタ。

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 保持するイテレータ。 |
| end | const typename Dict::map_t::const_iterator\& | コンテナの終端を指すイテレータ。 |

## DictionaryIterator::DictionaryIterator(DictionaryIterator\&&) コンストラクタ

ムーブコンストラクタ。

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(DictionaryIterator &&other) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [DictionaryIterator](../)\&& | データの移動元となるイテレータ。 |

## 関連項目

* クラス [DictionaryIterator](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)