---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 将指定幻灯片的副本添加到集合的末尾。
type: docs
weight: 53
url: /zh/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) 方法

将指定幻灯片的副本添加到集合的末尾。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 用于克隆。 |

### 返回值

新幻灯片。

## 备注

在不同演示文稿之间克隆幻灯片时，也可以克隆幻灯片的母版。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止也不会被记录。如果需要对克隆过程进行更细致的控制，可使用 [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) 或 [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) 来克隆幻灯片，使用 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) 或 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) 来克隆布局，使用 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) 来克隆母版。

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) 方法

将指定幻灯片的副本添加到指定章节的末尾。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 用于克隆。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用于新幻灯片。 |

### 返回值

新幻灯片。

## 备注

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// 现在第二个章节包含了第一张幻灯片的副本。
```

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) 方法

将指定幻灯片的副本添加到集合的末尾。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 用于克隆。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 用于新幻灯片的布局幻灯片。 |

### 返回值

新幻灯片。

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) 方法

将指定源幻灯片的副本添加到集合的末尾。将自动从指定的母版中选择合适的布局（合适的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果没有合适的布局，则会克隆源幻灯片的布局（当 allowCloneMissingLayout 为 true 时），否则将抛出 PptxEditException（当 allowCloneMissingLayout 为 false 时）。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 用于克隆。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 用于新幻灯片的母版幻灯片。 |
| allowCloneMissingLayout | **bool** | 如果在指定的母版中没有合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则将抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |

### 返回值

新幻灯片。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)