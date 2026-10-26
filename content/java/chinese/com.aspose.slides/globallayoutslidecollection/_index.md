---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides for Java API 参考
description: 表示演示文稿中所有布局幻灯片的集合。
type: docs
url: /zh/com.aspose.slides/globallayoutslidecollection/
---
**继承:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**全部实现的接口:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
``` 
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

表示演示文稿中所有布局幻灯片的集合。扩展 LayoutSlideCollection 类，提供在合并各个主布局幻灯片集合的上下文中添加/克隆布局幻灯片的方法。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 向演示文稿添加指定布局幻灯片的副本。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 向演示文稿添加指定布局幻灯片的副本。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 向演示文稿添加新的布局幻灯片。 |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

向演示文稿添加指定布局幻灯片的副本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |

--------------------

当在不同演示文稿之间克隆布局时，布局的母版也可以一起克隆，以保持源格式。内部注册表用于自动跟踪已克隆的母版，以防止同一母版幻灯片被多次克隆。手动克隆母版幻灯片既不会被阻止，也不会被注册。

**返回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

向演示文稿添加指定布局幻灯片的副本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新布局的母版幻灯片。 |

--------------------

1) 新布局将在目标演示文稿中链接到指定的母版。因此这相当于 PowerPoint 中使用 “使用目标主题” 选项的复制/粘贴。2) 此方法的类似方式是通过属性 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 访问的方法 [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-)。

**返回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

向演示文稿添加新的布局幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新布局的母版幻灯片。 |
| layoutType | byte | 新布局的布局类型。支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。其他布局类型目前不受支持：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null，则会根据传入的布局类型自动生成名称（例如 “Title Slide” 或 “1_Title Slide”, “2_…”，依此类推）。 |

--------------------

1) 当 layoutType 为 SlideLayoutType.Custom 时，添加的布局不包含占位符和形状。2) 此方法的类似方式是通过属性 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 访问的方法 [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-)。

**返回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。