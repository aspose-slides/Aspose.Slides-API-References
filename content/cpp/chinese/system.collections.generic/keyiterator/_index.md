---
title: KeyIterator
second_title: Aspose.Slides C++ API 参考
description: 提供键访问的字典迭代器。
type: docs
weight: 365
url: /zh/system.collections.generic/keyiterator/
---
## KeyIterator 类

[Dictionary](../dictionary/) 提供键访问的迭代器。
```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 类。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | 克隆当前迭代器。 |
| void [DecrementIterator](./decrementiterator/)() override | 将迭代器后退一步。 |
| void [IncrementIterator](./incrementiterator/)() override | 将迭代器前进一步。 |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 构造函数。 |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 构造函数。 |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | 移动构造函数。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 将迭代器移动指定的步数。 |
| virtual  [~KeyIterator](./~keyiterator/)() | 析构函数。 |

## 另见

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)