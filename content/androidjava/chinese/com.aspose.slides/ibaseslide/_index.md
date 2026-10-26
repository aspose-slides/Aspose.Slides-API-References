---
title: IBaseSlide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示所有幻灯片类型的通用数据。
type: docs
url: /zh/com.aspose.slides/ibaseslide/
---
**所有已实现的接口：**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
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
| [getCustomData()](#getCustomData--) | 返回幻灯片的自定义数据。 |
| [getTimeline()](#getTimeline--) | 返回动画时间轴对象。 |
| [getSlideShowTransition()](#getSlideShowTransition--) | 返回 TransitionEx 对象，该对象包含有关指定幻灯片在放映过程中如何前进的信息。 |
| [getBackground()](#getBackground--) | 返回幻灯片的背景。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对包含的超链接的便捷访问。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否应在幻灯片上显示母版幻灯片上的形状。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否应在幻灯片上显示母版幻灯片上的形状。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 查找具有指定替代文本的形状的首次出现。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有可接受的形状的所有段落中合并具有相同格式的文本段落。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 确定两个 IBaseSlide 实例是否相等。 |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

返回幻灯片的形状。只读 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**返回：**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

返回幻灯片上 ActiveX 控件的集合。只读 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**返回：**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public abstract String getName()
```

返回或设置幻灯片的名称。读写 String。

**返回：**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回或设置幻灯片的名称。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

返回幻灯片的 ID。只读 long。

**返回：**
long

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

返回幻灯片的自定义数据。只读 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回：**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

返回动画时间轴对象。只读 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**返回：**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

返回 TransitionEx 对象，该对象包含有关指定幻灯片在放映过程中如何前进的信息。只读 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**返回：**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

返回幻灯片的背景。只读 [IBackground](../../com.aspose.slides/ibackground)。

**返回：**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

提供对包含的超链接的便捷访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

指定是否应在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。读写 boolean。

**返回：**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

指定是否应在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

查找具有指定替代文本的形状的首次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| altText | java.lang.String | 替代文本。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - ShapeEx 对象或 null。

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

在所有可接受的形状的所有段落中合并具有相同格式的文本段落。

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画及其他设置等均相等，则两张幻灯片相等。比较不考虑唯一标识符值，例如 SlideId，以及动态内容，例如日期占位符中的当前日期值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 与当前 IBaseSlide 进行比较的 IBaseSlide。 |

**返回：**
boolean - **true**（如果指定的 IBaseSlide 与当前 IBaseSlide 相等）；否则，**false**。