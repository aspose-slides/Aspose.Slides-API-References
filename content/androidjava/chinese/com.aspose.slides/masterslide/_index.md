---
title: MasterSlide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示演示文稿中的母版幻灯片。
type: docs
url: /zh/com.aspose.slides/masterslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

表示演示文稿中的母版幻灯片。
## Methods

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回 主幻灯片的 HeaderFooter 管理器。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 基于当前母版创建一个新母版，应用外部主题并将创建的母版应用于所有依赖的幻灯片。 |
| [getTitleStyle()](#getTitleStyle--) | 返回 标题文本的样式。 |
| [getBodyStyle()](#getBodyStyle--) | 返回 正文文本的样式。 |
| [getOtherStyle()](#getOtherStyle--) | 返回 其他文本的样式。 |
| [getLayoutSlides()](#getLayoutSlides--) | 返回 此母版的子布局幻灯片集合。 |
| [getPreserve()](#getPreserve--) | 确定当所有跟随该母版的幻灯片被删除时，是否删除对应的母版。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 确定当所有跟随该母版的幻灯片被删除时，是否删除对应的母版。 |
| [getDependingSlides()](#getDependingSlides--) | 返回 一个包含所有依赖此母版的幻灯片的数组。 |
| [hasDependingSlides()](#hasDependingSlides--) | 如果存在至少一个依赖此母版的幻灯片，则返回 true。 |
| [getThemeManager()](#getThemeManager--) | 返回 主题管理器。 |
| [getName()](#getName--) | 返回或设置 母版幻灯片的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或设置 母版幻灯片的名称。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定 是否在幻灯片上显示母版幻灯片上的形状。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定 是否在幻灯片上显示母版幻灯片上的形状。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回 母版幻灯片的绘图参考线集合。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

返回 主幻灯片的 HeaderFooter 管理器。只读 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**返回:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

基于当前母版创建一个新母版，应用外部主题并将创建的母版应用于所有依赖的幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 外部主题文件 (.thmx) 的路径。 |

**返回:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新的主题化 MasterSlide。

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

返回 标题文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

返回 正文文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

返回 其他文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

返回 此母版的子布局幻灯片集合。只读 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

您可以通过使用 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 属性访问用于添加/插入/删除/克隆布局幻灯片的备用 API。

**返回:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

确定当所有跟随该母版的幻灯片被删除时，是否删除对应的母版。注意：Aspose.Slides 永不自行删除任何未使用的母版，要实际删除未使用的母版，请调用 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) 读/写  boolean 。

**返回:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

确定当所有跟随该母版的幻灯片被删除时，是否删除对应的母版。注意：Aspose.Slides 永不自行删除任何未使用的母版，要实际删除未使用的母版，请调用 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) 读/写  boolean 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

返回 一个包含所有依赖此母版的幻灯片的数组。

**返回:**
com.aspose.slides.ISlide[] - 包含 [ISlide](../../com.aspose.slides/islide) 的数组。

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

如果存在至少一个依赖此母版的幻灯片，则返回 true。只读  boolean 。

**返回:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

返回 主题管理器。只读 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**返回:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

返回或设置 母版幻灯片的名称。读/写 String。

**返回:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

返回或设置 母版幻灯片的名称。读/写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定 是否在幻灯片上显示母版幻灯片上的形状。对于母版本身，此属性始终返回 false。读/写  boolean 。

**返回:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定 是否在幻灯片上显示母版幻灯片上的形状。对于母版本身，此属性始终返回 false。读/写  boolean 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

返回 母版幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)