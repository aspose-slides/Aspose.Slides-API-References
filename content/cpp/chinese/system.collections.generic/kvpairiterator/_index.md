---
title: KVPairIterator
second_title: Aspose.Slides for C++ API 参考
description: "适配迭代器，将 std::pair 包装为来自 Dictionary 的 KVPair。"
type: docs
weight: 391
url: /zh/system.collections.generic/kvpairiterator/
---
## KVPairIterator 类


适配迭代器，将 std::pair 包装为来自 [Dictionary](../dictionary/) 的 KVPair。

```cpp
template<typename KVPair,typename Container>class KVPairIterator
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| KVPair | 必需的返回类型 |
| Container | 包装的容器类型 |
## 方法

| 方法 | 描述 |
| --- | --- |
|  [KVPairIterator](./kvpairiterator/)(typename Container::const_iterator) |  |
| KVPair [operator*](./operator_star/)() const |  |
| [KVPairIterator](./)\& [operator++](./operator_plus_plus/)() |  |
| [KVPairIterator](./) [operator++](./operator_plus_plus/)(int) |  |
| [KVPairIterator](./)\& [operator--](./operator_minus_minus/)() |  |
| [KVPairIterator](./) [operator--](./operator_minus_minus/)(int) |  |
## 类型定义

| 类型别名 | 描述 |
| --- | --- |
| [iterator_category](./iterator_category/) |  |
| [value_type](./value_type/) |  |
| [difference_type](./difference_type/) |  |
| [pointer](./pointer/) |  |
| [reference](./reference/) |  |

## 另请参见

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)