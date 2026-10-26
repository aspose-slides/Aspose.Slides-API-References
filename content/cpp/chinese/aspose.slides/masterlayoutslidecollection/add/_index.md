---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 在集合末尾添加一个新的布局幻灯片。
type: docs
weight: 27
url: /zh/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) 方法

在集合末尾添加一个新的布局幻灯片。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 用于新布局的布局类型。支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。当前不支持的其他布局类型：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 返回值

已添加的幻灯片。

## 备注

1) 为 *layoutType* 的值 [SlideLayoutType::Custom](../../slidelayouttype/) 添加的布局不包含占位符和形状。2) 此方法的对应方法是 [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/)，通过 [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 属性访问。

## 另见

* 枚举 [SlideLayoutType](../../slidelayouttype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [String](../../../system/string/)
* 类 [MasterLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)