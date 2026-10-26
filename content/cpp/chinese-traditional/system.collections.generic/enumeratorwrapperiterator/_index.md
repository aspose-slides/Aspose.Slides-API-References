---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides for C++ API 參考
description: 將預先建立的列舉器包裝起來，並將所有呼叫重新導向至該列舉器。
type: docs
weight: 196
url: /zh-hant/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator 類別

將預先建立的列舉器包裝起來，並將所有呼叫重新導向至該列舉器。

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Template parameters

| 參數 | 描述 |
| --- | --- |
| Element | Element 型別。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | 複製目前的迭代器。 |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | 將迭代器向前移動一步。必須更新 m_is_end 和 m_pointer。 |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | 檢查兩個迭代器是否指向相同的項目。 |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | 析構函式。 |

## 參見

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)