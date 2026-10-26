---
title: ILayoutSlide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个布局幻灯片。
type: docs
url: /zh/com.aspose.slides/ilayoutslide/
---
**所有实现的接口：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

表示布局幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回布局幻灯片的 HeaderFooter 管理器。 |
| [getPlaceholderManager()](#getPlaceholderManager--) | 返回布局幻灯片的占位符管理器。 |
| [getMasterSlide()](#getMasterSlide--) | 返回或设置布局的母版幻灯片。 |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | 返回或设置布局的母版幻灯片。 |
| [getLayoutType()](#getLayoutType--) | 返回此布局幻灯片的布局类型。 |
| [hasDependingSlides()](#hasDependingSlides--) | 如果存在至少一个依赖此布局幻灯片的幻灯片，则返回 true。 |
| [getDependingSlides()](#getDependingSlides--) | 返回一个包含所有依赖此布局幻灯片的幻灯片的数组。 |
| [remove()](#remove--) | 从演示文稿中移除布局。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回布局幻灯片的绘图指南集合。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

返回布局幻灯片的 HeaderFooter 管理器。只读 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)。

**返回：**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

返回布局幻灯片的占位符管理器。只读 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)。

**返回：**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

返回或设置布局的母版幻灯片。读写 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**返回：**
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

返回或设置布局的母版幻灯片。读写 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

返回此布局幻灯片的布局类型。只读 [SlideLayoutType](../../com.aspose.slides/slidelayouttype)。

**返回：**
byte

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

如果存在至少一个依赖此布局幻灯片的幻灯片，则返回 true。只读 boolean。

**返回：**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

返回一个包含所有依赖此布局幻灯片的幻灯片的数组。

**返回：**
com.aspose.slides.ISlide[] - Array with all slides, which depend on this layout slide

### remove() {#remove--}
```
public abstract void remove()
```

从演示文稿中移除布局。

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

返回布局幻灯片的绘图指南集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Adding the new vertical drawing guide to the left of the slide center
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)