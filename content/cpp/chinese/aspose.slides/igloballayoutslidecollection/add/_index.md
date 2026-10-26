---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 向演示文稿添加一个新的版式幻灯片。
type: docs
weight: 14
url: /zh/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) 方法

向演示文稿添加一个新的版式幻灯片。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 用于新版式的母版幻灯片。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 用于新版式的布局类型。支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。当前不支持的布局类型：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 返回值

已添加的幻灯片。

## 备注

1) 对于 *layoutType* 的值 [SlideLayoutType::Custom](../../slidelayouttype/) 添加的布局不包含占位符和形状。 2) 此方法的对应方法是 [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/)，可通过 [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) 属性访问。

## 另见

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [IMasterSlide](../../imasterslide/)
* 类 [String](../../../system/string/)
* 类 [IGlobalLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)