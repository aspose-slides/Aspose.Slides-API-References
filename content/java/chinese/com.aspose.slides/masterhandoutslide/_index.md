---
title: MasterHandoutSlide
second_title: Aspose.Slides for Java API 参考
description: 表示讲义的母版幻灯片。
type: docs
url: /zh/com.aspose.slides/masterhandoutslide/
---
**继承：**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**所有实现的接口：**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

表示讲义的母版幻灯片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在幻灯片上显示母版幻灯片中的形状。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在幻灯片上显示母版幻灯片中的形状。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回母版讲义幻灯片的 HeaderFooter 管理器。 |
| [getThemeManager()](#getThemeManager--) | 返回主题管理器。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回母版讲义幻灯片的绘图参考线集合。 |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在幻灯片上显示母版幻灯片中的形状。对于母版幻灯片本身，此属性始终返回 false。可读写 boolean。

**返回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在幻灯片上显示母版幻灯片中的形状。对于母版幻灯片本身，此属性始终返回 false。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

返回母版讲义幻灯片的 HeaderFooter 管理器。只读 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**返回：**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

返回主题管理器。只读 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**返回：**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

返回母版讲义幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // 在幻灯片中心上方添加新的水平绘图参考线
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)