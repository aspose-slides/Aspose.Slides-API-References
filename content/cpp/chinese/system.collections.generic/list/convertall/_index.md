---
title: ConvertAll()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个已转换为不同类型的元素列表。
type: docs
weight: 352
url: /zh/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) 方法

创建一个已转换为不同类型的元素列表。

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| OutputType | 输出列表元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | 用于项目转换的转换器。 |

### 返回值

一个新创建的已转换元素列表。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)