---
title: KeyIterator()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.collections.generic/keyiterator/keyiterator/
---
## KeyIterator::KeyIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) コンストラクタ

コンストラクタ。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 保持するイテレータ。 |
| end | typename Dict::map_t::const_iterator\&& | コンテナの末尾を指すイテレータ。 |

## KeyIterator::KeyIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) コンストラクタ

コンストラクタ。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 保持するイテレータ。 |
| end | const typename Dict::map_t::const_iterator\& | コンテナの末尾を指すイテレータ。 |

## KeyIterator::KeyIterator(KeyIterator\&&) コンストラクタ

ムーブコンストラクタ。

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(KeyIterator &&other) noexcept
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| other | [KeyIterator](../)\&& | データを移動するイテレータ。 |

## 参照

* クラス [KeyIterator](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)