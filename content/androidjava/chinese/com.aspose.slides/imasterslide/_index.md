---
title: IMasterSlide
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示演示文稿中的母版幻灯片。
type: docs
url: /zh/com.aspose.slides/imasterslide/
---
**所有已实现的接口:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

表示演示文稿中的母版幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回母版幻灯片的 HeaderFooter 管理器。 |
| [getTitleStyle()](#getTitleStyle--) | 返回标题文本的样式。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 基于当前母版创建新母版，应用外部主题，并将创建的母版应用到所有依赖的幻灯片。 |
| [getBodyStyle()](#getBodyStyle--) | 返回正文文本的样式。 |
| [getOtherStyle()](#getOtherStyle--) | 返回其他文本的样式。 |
| [getLayoutSlides()](#getLayoutSlides--) | 返回此母版的子布局幻灯片集合。 |
| [getPreserve()](#getPreserve--) | 确定在删除所有跟随该母版的幻灯片时是否删除对应的母版。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 确定在删除所有跟随该母版的幻灯片时是否删除对应的母版。 |
| [hasDependingSlides()](#hasDependingSlides--) | 若至少存在一张依赖此母版的幻灯片，则返回 true。 |
| [getDependingSlides()](#getDependingSlides--) | 返回一个数组，包含所有依赖此母版的幻灯片。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回母版幻灯片的绘图参考线集合。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

返回母版幻灯片的 HeaderFooter 管理器。只读 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**返回:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

返回标题文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

基于当前母版创建新母版，应用外部主题，并将创建的母版应用到所有依赖的幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 外部主题文件（.thmx）的路径。 |

**返回:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新的主题化 MasterSlide。

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

返回正文文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

返回其他文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

返回此母版的子布局幻灯片集合。只读 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

您可以通过使用 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 属性访问用于添加/插入/删除/克隆布局幻灯片的备用 API。

**返回:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

确定在删除所有跟随该母版的幻灯片时是否删除对应的母版。注意：Aspose.Slides 永不会自行删除未使用的母版，若要实际删除未使用的母版，请调用 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-)。读写 boolean。

**返回:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

确定在删除所有跟随该母版的幻灯片时是否删除对应的母版。注意：Aspose.Slides 永不会自行删除未使用的母版，若要实际删除未使用的母版，请调用 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-)。读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

若至少存在一张依赖此母版的幻灯片，则返回 true。只读 boolean。

**返回:**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

返回一个数组，包含所有依赖此母版的幻灯片。

**返回:**
com.aspose.slides.ISlide[] - 依赖此母版的 [ISlide](../../com.aspose.slides/islide) 数组

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

返回母版幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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