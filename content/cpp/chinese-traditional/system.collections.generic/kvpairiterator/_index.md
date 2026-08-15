---
title: KVPairIterator
second_title: Aspose.Slides for C++ API 參考
description: "適配迭代器，將 std::pair 包裝為來自 Dictionary 所期望的 KVPair。"
type: docs
weight: 391
url: /zh-hant/system.collections.generic/kvpairiterator/
---
## KVPairIterator 類別

Adapting iterator, wraps std::pair into KVPair expected from [Dictionary](../dictionary/).

```cpp
template<typename KVPair,typename Container>class KVPairIterator
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| KVPair | 必要的返回類型 |
| Container | 封裝的容器類型 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [KVPairIterator](./kvpairiterator/)(typename Container::const_iterator) |  |
| KVPair [operator*](./operator_star/)() const |  |
| [KVPairIterator](./)\& [operator++](./operator_plus_plus/)() |  |
| [KVPairIterator](./) [operator++](./operator_plus_plus/)(int) |  |
| [KVPairIterator](./)\& [operator--](./operator_minus_minus/)() |  |
| [KVPairIterator](./) [operator--](./operator_minus_minus/)(int) |  |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [iterator_category](./iterator_category/) |  |
| [value_type](./value_type/) |  |
| [difference_type](./difference_type/) |  |
| [pointer](./pointer/) |  |
| [reference](./reference/) |  |

## 另見

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)