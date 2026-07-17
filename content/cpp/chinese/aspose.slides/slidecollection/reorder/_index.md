---
title: Reorder()
second_title: Aspose.Slides C++ API 参考
description: 将幻灯片从集合中移动到指定位置。
type: docs
weight: 157
url: /zh/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) 方法

将幻灯片从集合中移动到指定位置。

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 目标索引。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要移动。 |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) 方法

将幻灯片从集合中移动到指定位置。[Slides](../../) 将从 index 开始按它们在列表中出现的顺序放置。

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 目标索引。 |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) 要移动。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)