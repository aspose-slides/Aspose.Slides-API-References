---
title: Insert()
second_title: Aspose.Slides for C++ API 参考
description: 在集合的指定位置插入新的布局幻灯片。
type: docs
weight: 40
url: /zh/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) 方法

将新的布局幻灯片插入到集合的指定位置。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新布局的布局类型。支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。其他布局类型当前不受支持：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 "Title Slide" 或 "1_Title Slide"，"2_..", 等）。 |

### 返回值

已插入的幻灯片。

## 备注

针对 *layoutType* 为 [SlideLayoutType::Custom](../../slidelayouttype/) 的已插入布局不包含占位符和形状。

## 另见

* 枚举 [SlideLayoutType](../../slidelayouttype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [String](../../../system/string/)
* 类 [MasterLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)