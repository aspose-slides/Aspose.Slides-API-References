---
title: LayoutSlide
second_title: Aspose.Slides for Java API 参考
description: 表示布局幻灯片。
type: docs
url: /zh/com.aspose.slides/layoutslide/
---
**继承:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**所有实现的接口:**  
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)  
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

表示布局幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回布局幻灯片的 HeaderFooter 管理器。 |
| [getPlaceholderManager()](#getPlaceholderManager--) | 返回布局幻灯片的 placeholder manager。 |
| [getMasterSlide()](#getMasterSlide--) | 返回或设置布局的 master slide。 |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | 返回或设置布局的 master slide。 |
| [remove()](#remove--) | 从演示文稿中移除布局。 |
| [getThemeManager()](#getThemeManager--) | 返回覆盖 theme manager。 |
| [getLayoutType()](#getLayoutType--) | 返回此布局幻灯片的布局类型。 |
| [getDependingSlides()](#getDependingSlides--) | 返回一个数组，包含所有依赖此布局幻灯片的幻灯片。 |
| [hasDependingSlides()](#hasDependingSlides--) | 如果存在至少一个依赖此布局幻灯片的幻灯片，则返回 true。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在幻灯片上显示 master slide 上的形状。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在幻灯片上显示 master slide 上的形状。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回布局幻灯片的绘图指南集合。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

返回布局幻灯片的 HeaderFooter 管理器。只读 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)。

**返回:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

返回布局幻灯片的 placeholder manager。只读 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)。

**返回:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

返回或设置布局的 master slide。读/写 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**返回:**
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

返回或设置布局的 master slide。读/写 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```

从演示文稿中移除布局。

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

返回覆盖 theme manager。只读 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**返回:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

返回此布局幻灯片的布局类型。只读 [SlideLayoutType](../../com.aspose.slides/slidelayouttype)。

**返回:**
byte

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

返回一个数组，包含所有依赖此布局幻灯片的幻灯片。

**返回:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

如果存在至少一个依赖此布局幻灯片的幻灯片，则返回 true。只读 boolean 。

**返回:**
boolean

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在幻灯片上显示 master slide 上的形状。读/写 boolean 。

**返回:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在幻灯片上显示 master slide 上的形状。读/写 boolean 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

返回布局幻灯片的绘图指南集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // 在幻灯片中心左侧添加新的垂直绘图指南
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)