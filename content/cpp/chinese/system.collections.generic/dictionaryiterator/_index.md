---
title: DictionaryIterator
second_title: Aspose.Slides for C++ API 参考
description: 提供 KeyValuePair 表示法的字典迭代器。
type: docs
weight: 157
url: /zh/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator 类

[Dictionary](../dictionary/) 迭代器，提供 [KeyValuePair](../keyvaluepair/) 符号表示。

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 类。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | 克隆当前迭代器。 |
| void [DecrementIterator](./decrementiterator/)() override | 将迭代器向后移动一步。 |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 构造函数。 |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 构造函数。 |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | 移动构造函数。 |
| void [IncrementIterator](./incrementiterator/)() override | 将迭代器向前移动一步。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 将迭代器按指定的步数移动。 |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | 析构函数。 |

## 另见

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)