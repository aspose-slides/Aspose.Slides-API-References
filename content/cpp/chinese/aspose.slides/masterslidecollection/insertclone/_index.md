---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 将指定母版幻灯片的副本插入集合的指定位置。关联的布局幻灯片也会被复制。
type: docs
weight: 105
url: /zh/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) 方法

插入指定母版幻灯片的副本到集合的指定位置。关联的布局幻灯片也会被复制。

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) 用于克隆。 |

### 返回值

已插入的母版幻灯片。

## 备注

以下示例展示了如何在另一个 PowerPoint [Presentation](../../presentation/) 中克隆母版幻灯片。

```cpp
// 实例化 Presentation 类以加载源演示文稿文件
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// 实例化 Presentation 类用于目标演示文稿（要克隆幻灯片的地方）
auto destPres = System::MakeObject<Presentation>();

// 从源演示文稿的幻灯片集合中实例化 ISlide，连同
// 母版幻灯片
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// 获取目标演示文稿的母版幻灯片
auto masters = destPres->get_Masters();
// 将所需的母版幻灯片从源演示文稿克隆到
// 目标演示文稿的母版集合中
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// 目标演示文稿中的幻灯片集合
auto slides = destPres->get_Slides();
// 将源幻灯片克隆到目标幻灯片集合。
slides->AddClone(sourceSlide, iSlide, true);
// 将目标演示文稿保存到磁盘
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMasterSlide](../../imasterslide/)
* 类 [MasterSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)