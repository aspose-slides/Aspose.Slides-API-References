---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides 在 Android 上的 Java API 参考
description: 表示演示文稿中所有布局幻灯片的集合。
type: docs
url: /zh/com.aspose.slides/igloballayoutslidecollection/
---
**所有实现的接口：**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

表示演示文稿中所有布局幻灯片的集合。扩展 ILayoutSlideCollection 接口，提供在合并主布局幻灯片的各个集合的上下文中添加/克隆布局幻灯片的方法。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 将指定布局幻灯片的副本添加到演示文稿中。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 将指定布局幻灯片的副本添加到演示文稿中。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 在演示文稿中添加一个新的布局幻灯片。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

将指定布局幻灯片的副本添加到演示文稿中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |

--------------------

在不同演示文稿之间克隆布局时，布局的母版也可以被克隆，以保留源格式。内部注册表用于跟踪自动克隆的母版，防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止，也不会被记录。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

将指定布局幻灯片的副本添加到演示文稿中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新布局的母版幻灯片。 |

--------------------

新布局将在目标演示文稿中与指定的母版关联。这相当于在 PowerPoint 中使用“使用目标主题”选项的复制/粘贴操作。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

在演示文稿中添加一个新的布局幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新布局的母版幻灯片。 |
| layoutType | byte | 新布局的布局类型。支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。当前不支持以下布局类型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 “Title Slide” 或 “1\_Title Slide”、 “2\_..” 等）。 |

--------------------

1) 对于 layoutType 为 SlideLayoutType.Custom 的值，添加的布局不包含占位符和形状。2) 此方法的等价方法是 [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-)，通过 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 属性访问。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。