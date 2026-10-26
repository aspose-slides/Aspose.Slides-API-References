---
title: ToArray()
second_title: Aspose.Slides for C++ API 参考
description: 创建并返回一个包含所有幻灯片的数组。
type: docs
weight: 92
url: /zh/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() 方法

创建并返回一个包含所有幻灯片的数组。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### 返回值

Array of [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) 方法

创建并返回一个包含指定范围内所有幻灯片的数组。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **int32_t** | 要添加的第一张幻灯片的索引。 |
| count | **int32_t** | 要添加的幻灯片数量。 |

### 返回值

Array of [ISlide](../../islide/)

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [ISlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)