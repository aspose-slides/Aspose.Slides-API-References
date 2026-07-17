---
title: Reorder()
second_title: Aspose.Slides C++ API 参考
description: 将幻灯片从集合中移动到指定位置。
type: docs
weight: 105
url: /zh/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) 方法

将幻灯片从集合中移动到指定位置。

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 目标索引。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要移动。 |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) 方法

将多个幻灯片从集合中移动到指定位置。[Slides](../../) 将按照它们在列表中出现的顺序，从 index 开始放置。

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 目标索引。 |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) 要移动。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ISlide](../../islide/)
* 类 [ISlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)