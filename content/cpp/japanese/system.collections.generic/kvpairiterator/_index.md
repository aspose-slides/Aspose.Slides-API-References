---
title: KVPairIterator
second_title: Aspose.Slides for C++ API リファレンス
description: "イテレータを適応し、std::pair を Dictionary から期待される KVPair にラップします。"
type: docs
weight: 391
url: /ja/system.collections.generic/kvpairiterator/
---
## KVPairIterator クラス

イテレータを適応し、std::pair を [Dictionary](../dictionary/) から期待される KVPair にラップします。

```cpp
template<typename KVPair,typename Container>class KVPairIterator
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| KVPair | 必要な戻り値の型 |
| Container | ラップされたコンテナ型 |

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [KVPairIterator](./kvpairiterator/)(typename Container::const_iterator) |  |
| KVPair [operator*](./operator_star/)() const |  |
| [KVPairIterator](./)\& [operator++](./operator_plus_plus/)() |  |
| [KVPairIterator](./) [operator++](./operator_plus_plus/)(int) |  |
| [KVPairIterator](./)\& [operator--](./operator_minus_minus/)() |  |
| [KVPairIterator](./) [operator--](./operator_minus_minus/)(int) |  |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [iterator_category](./iterator_category/) |  |
| [value_type](./value_type/) |  |
| [difference_type](./difference_type/) |  |
| [pointer](./pointer/) |  |
| [reference](./reference/) |  |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)