---
title: InsertClone()
second_title: Aspose.Slides for C++ API 参考
description: 在集合的指定位置插入指定布局幻灯片的副本。
type: docs
weight: 14
url: /zh/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) 方法

将指定布局幻灯片的副本插入到集合的指定位置。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 进行克隆。 |

### 返回值

已插入的幻灯片。

## 备注

新的布局将与此布局幻灯片集合的父母版幻灯片关联。因此这相当于在 PowerPoint 中使用 “使用目标主题” 选项的复制/粘贴操作。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [MasterLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)