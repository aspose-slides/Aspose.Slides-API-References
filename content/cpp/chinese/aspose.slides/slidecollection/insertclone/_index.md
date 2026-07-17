---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 在集合的指定位置插入指定幻灯片的副本。
type: docs
weight: 66
url: /zh/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) 方法

在集合的指定位置插入指定幻灯片的副本。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 用于克隆。 |

### 返回值

已插入的幻灯片。

## 备注

在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止同一母版幻灯片创建多个克隆。手动克隆母版幻灯片既不会被阻止，也不会被注册。如果需要对克隆过程进行更细致的控制，可使用 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) 或 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) 来克隆幻灯片，使用 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) 来克隆母版。

以下示例展示了如何在 [Presentation](../../presentation/) 中的其他位置进行克隆。  
```cpp
// 实例化表示演示文稿文件的 Presentation 类
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// 将所需幻灯片克隆到同一演示文稿中幻灯片集合的末尾
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// 将所需幻灯片克隆到同一演示文稿中的指定索引位置
slides->InsertClone(2, slides->idx_get(1));
// 将修改后的演示文稿写入磁盘
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何在 [Presentation](../../presentation/) 中的其他位置进行克隆。  
```cpp
// 实例化 Presentation 类以加载源演示文稿文件
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// 实例化用于目标 PPTX 的 Presentation 类（幻灯片将被克隆到此）
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// 将目标演示文稿写入磁盘
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) 方法

在集合的指定位置插入指定幻灯片的副本。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 用于克隆。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新幻灯片的布局幻灯片。 |

### 返回值

已插入的幻灯片。

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) 方法

在集合的指定位置插入指定源幻灯片的副本。将自动从指定的母版中选择合适的布局（合适的布局是与源幻灯片布局具有相同类型或名称的布局）。如果在指定的母版中没有合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 用于克隆。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新幻灯片的母版幻灯片。 |
| allowCloneMissingLayout | **bool** | 如果在指定的母版中没有合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |

### 返回值

已插入的幻灯片。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [SlideCollection](../)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [IMasterSlide](../../imasterslide/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)