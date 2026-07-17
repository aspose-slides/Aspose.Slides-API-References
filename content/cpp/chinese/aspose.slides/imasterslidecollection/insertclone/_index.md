---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 在集合的指定位置插入指定母版幻灯片的副本。关联的布局幻灯片也会被复制。
type: docs
weight: 66
url: /zh/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) 方法

在集合的指定位置插入指定母版幻灯片的副本。关联的布局幻灯片也会被复制。

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) 用于克隆。 |

### 返回值

已插入的母版幻灯片。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMasterSlide](../../imasterslide/)
* 类 [IMasterSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)