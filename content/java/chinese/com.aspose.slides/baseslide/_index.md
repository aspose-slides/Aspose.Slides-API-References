---
title: BaseSlide
second_title: Aspose.Slides for Java API 参考
description: 表示所有幻灯片类型的通用数据。
type: docs
url: /zh/com.aspose.slides/baseslide/
---
**继承:**
java.lang.Object

**实现的所有接口:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

表示所有幻灯片类型的通用数据。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapes()](#getShapes--) | 返回幻灯片的形状。 |
| [getControls()](#getControls--) | 返回幻灯片上 ActiveX 控件的集合。 |
| [getName()](#getName--) | 返回或设置幻灯片的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或设置幻灯片的名称。 |
| [getSlideId()](#getSlideId--) | 返回幻灯片的 ID。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 确定两个 IBaseSlide 实例是否相等。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有可接受形状的所有段落中合并具有相同格式的文本段。 |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | 在所有可接受形状的所有段落中合并具有相同格式的文本段。 |
| [createThemeEffective()](#createThemeEffective--) | 返回此幻灯片的有效主题。 |
| [getCustomData()](#getCustomData--) | 返回幻灯片的自定义数据。 |
| [getTimeline()](#getTimeline--) | 返回动画时间线对象。 |
| [getSlideShowTransition()](#getSlideShowTransition--) | 返回 Transition 对象，其中包含指定幻灯片在放映期间如何前进的信息。 |
| [getBackground()](#getBackground--) | 返回幻灯片的背景。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对包含的超链接的便捷访问。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在幻灯片上显示母版幻灯片上的形状。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在幻灯片上显示母版幻灯片上的形状。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 查找具有指定替代文本的形状的第一次出现。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | 返回 IPresentation 接口。 |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

返回幻灯片的形状。只读 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**返回:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

返回幻灯片上 ActiveX 控件的集合。只读 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**返回:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public String getName()
```

返回或设置幻灯片的名称。可读写 String。

**返回:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

返回或设置幻灯片的名称。可读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

返回幻灯片的 ID。只读 long。

**返回:**
long

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

确定两个 IBaseSlide 实例是否相等。返回值根据幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画和其他设置等均相等，则两个幻灯片相等。比较不考虑唯一标识符值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

**返回:**
boolean -  **true**  如果指定的 IBaseSlide 等于当前的 IBaseSlide；否则，  **false** 。

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

在所有可接受形状的所有段落中合并具有相同格式的文本段。

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

在所有可接受形状的所有段落中合并具有相同格式的文本段。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

返回此幻灯片的有效主题。

**返回:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

返回幻灯片的自定义数据。只读 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

返回动画时间线对象。只读 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**返回:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

返回 Transition 对象，其中包含指定幻灯片在放映期间如何前进的信息。只读 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**返回:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

返回幻灯片的背景。只读 [IBackground](../../com.aspose.slides/ibackground)。

**返回:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供对包含的超链接的便捷访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。可读写 boolean。

**返回:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

查找具有指定替代文本的形状的首次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| altText | java.lang.String | 替代文本。 |

**返回:**
[IShape](../../com.aspose.slides/ishape) - 形状对象或 null。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 IPresentation 接口。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回基础幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)