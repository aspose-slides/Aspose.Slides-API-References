---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示已定义母版幻灯片的所有布局幻灯片的集合。
type: docs
url: /zh/com.aspose.slides/masterlayoutslidecollection/
---
**继承:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**所有实现的接口:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

表示已定义母版幻灯片的所有布局幻灯片的集合。扩展 LayoutSlideCollection 类，提供在母版布局幻灯片各自集合的上下文中添加/插入/删除/克隆/重新排序布局幻灯片的方法。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 将指定布局幻灯片的副本添加到集合的末尾。 |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定布局幻灯片的副本。 |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | 在集合的末尾添加一个新的布局幻灯片。 |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | 在集合的指定位置插入一个新的布局幻灯片。 |
| [removeAt(int index)](#removeAt-int-) | 删除集合中指定索引处的元素。 |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | 将布局幻灯片从集合中移动到指定位置。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

将指定布局幻灯片的副本添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |

--------------------

1) 新布局将链接到此布局幻灯片集合的父母版幻灯片。因此，这相当于在 PowerPoint 中使用“Use Destination Theme”选项的复制/粘贴。2) 此方法的对应方法是 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-)，通过 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 属性访问。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

在集合的指定位置插入指定布局幻灯片的副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |

--------------------

新布局将链接到此布局幻灯片集合的父母版幻灯片。因此，这相当于在 PowerPoint 中使用“Use Destination Theme”选项的复制/粘贴。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已插入的幻灯片。

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

在集合的末尾添加一个新的布局幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layoutType | byte | 新布局的布局类型。支持的布局类型有：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。当前不支持的布局类型有：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新布局的名称。如果提供的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据提供的布局类型自动生成名称（例如 “Title Slide” 或 “1_Title Slide”、“2_..” 等）。 |

--------------------

1) 当 layoutType 为 SlideLayoutType.Custom 时，添加的布局不包含占位符和形状。2) 此方法的对应方法是 [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-)，通过 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 属性访问。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已添加的幻灯片。

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

在集合的指定位置插入一个新的布局幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| layoutType | byte | 新布局的布局类型。支持的布局类型有：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。当前不支持的布局类型有：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新布局的名称。如果提供的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据提供的布局类型自动生成名称（例如 “Title Slide” 或 “1_Title Slide”、“2_..” 等）。 |

--------------------

当 layoutType 为 SlideLayoutType.Custom 时，插入的布局不包含占位符和形状。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已插入的幻灯片。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

删除集合中指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的元素的零基索引。 |

--------------------

1) 为避免抛出 PptxEditException，请先检查布局的 HasDependingSlides 属性。2) 您也可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法来简化代码。

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

将布局幻灯片从集合中移动到指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要移动的幻灯片。 |