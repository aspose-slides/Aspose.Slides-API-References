---
title: end()
second_title: Aspose.Slides C++ API 参考
description: 返回一个迭代器，指向容器中最后一个元素之后的键值元素的 KVPair 包装器。采用 C# 风格实现——迭代器应返回具有 get_Key() 和 get_Value() 接口的 KVPair 对象。该元素充当占位符；尝试访问它会导致未定义行为。
type: docs
weight: 235
url: /zh/system.collections.generic/basedictionary/end/
---
## BaseDictionary::end() const 方法

返回一个迭代器，指向容器中最后一个元素之后的 key-value 元素的 KVPair-wrapper。采用 C# 风格实现——迭代器应返回带有 get_Key() 和 get_Value() 接口的 KVPair-object。该元素充当占位符；尝试访问它会导致未定义行为。

```cpp
const_iterator System::Collections::Generic::BaseDictionary<Map>::end() const noexcept
```

### 返回值

指向集合中结束元素之后的理论元素的迭代器。

## 另请参见

* Typedef [const_iterator](../const_iterator/)
* 类 [BaseDictionary](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)