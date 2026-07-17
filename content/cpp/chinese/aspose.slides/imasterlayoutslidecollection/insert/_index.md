---
title: Insert()
second_title: Aspose.Slides for C++ API 参考
description: 在集合的指定位置插入一个新的布局幻灯片。
type: docs
weight: 40
url: /zh/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) 方法

在集合的指定位置插入一个新的布局幻灯片。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新布局的布局类型。支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。当前不支持的其他布局类型：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 返回值

插入的幻灯片。

## 备注

插入的布局（*layoutType* 的值为 [SlideLayoutType::Custom](../../slidelayouttype/)）不包含占位符和形状。

## 另见

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)