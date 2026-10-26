---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides C++ API 参考
description: 包装预创建的枚举器并将所有调用重定向到它的迭代器。
type: docs
weight: 196
url: /zh/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator 类

包装预创建的枚举器并将所有调用重定向到它的迭代器。

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Element | Element 类型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | 克隆当前迭代器。 |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | 将迭代器前进一步。必须更新 m_is_end 和 m_pointer。 |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | 检查两个迭代器是否指向相同的项。 |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | 析构函数。 |

## 另请参阅

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)