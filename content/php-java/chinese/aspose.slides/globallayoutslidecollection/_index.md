---
title: GlobalLayoutSlideCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection 类

表示演示文稿中所有布局幻灯片的集合。  
扩展 LayoutSlideCollection 类，提供在合并各个母版布局幻灯片集合的上下文中添加/克隆布局幻灯片的方法。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([MasterSlide](../masterslide), byte, String) | 向演示文稿添加一个新的布局幻灯片。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| master | [MasterSlide](../masterslide) | 新布局的母版幻灯片。 |
| layoutType | byte | 新布局的布局类型。支持的布局类型包括：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。当前不支持其他布局类型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | String | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 “Title Slide” 或 “1_Title Slide”、 “2_..” 等）。1) 对于 SlideLayoutType.Custom 的 layoutType 添加的布局不包含占位符和形状。2) 此方法的等价函数是通过 ( IMasterSlide#getLayoutSlides) 属性访问的 IMasterLayoutSlideCollection#add(byte,String) 方法。 |

**返回：**  
[LayoutSlide](../layoutslide)

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.ArgumentException | 如果布局名称 layoutName 已在母版的布局集合中使用，则抛出此异常。 |

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide)) | 向演示文稿添加指定布局幻灯片的副本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | 要克隆的幻灯片。当在不同演示文稿之间克隆布局时，布局的母版也可以被克隆，以保持源格式。内部注册表用于自动跟踪已克隆的母版，以防止同一母版幻灯片被多次克隆。手动克隆母版幻灯片既不会被阻止，也不会被记录。 |

**返回：**  
[LayoutSlide](../layoutslide)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide), [MasterSlide](../masterslide)) | 向演示文稿添加指定布局幻灯片的副本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | 要克隆的幻灯片。 |
| destMaster | [MasterSlide](../masterslide) | 新布局的母版幻灯片。1) 新布局将在目标演示文稿中链接到指定的母版。这相当于 PowerPoint 中使用 “使用目标主题” 选项的复制/粘贴。2) 此方法的等价函数是通过 ( IMasterSlide#getLayoutSlides) 属性访问的 IMasterLayoutSlideCollection#addClone(ILayoutSlide) 方法。 |

**返回：**  
[LayoutSlide](../layoutslide)

---