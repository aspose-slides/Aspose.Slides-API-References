---
title: ValueIterator
second_title: Aspose.Slides C++ API 参考
description: 提供值访问的字典迭代器。
type: docs
weight: 625
url: /zh/system.collections.generic/valueiterator/
---
## ValueIterator 类

[Dictionary](../dictionary/) 提供值访问的迭代器。

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 类。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | 克隆当前迭代器。 |
| void [DecrementIterator](./decrementiterator/)() override | 将迭代器向后移动一步。 |
| void [IncrementIterator](./incrementiterator/)() override | 将迭代器向前移动一步。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 按指定的步数移动迭代器。 |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 构造函数。 |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 构造函数。 |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | 移动构造函数。 |
| virtual  [~ValueIterator](./~valueiterator/)() | 析构函数。 |

## 另请参阅

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)