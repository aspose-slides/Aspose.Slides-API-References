---
title: MasterNotesSlide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示备注的母版幻灯片。
type: docs
url: /zh/com.aspose.slides/masternotesslide/
---
**继承：**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**所有实现的接口：**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

表示备注的母版幻灯片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定母版幻灯片上的形状是否应显示在幻灯片上。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定母版幻灯片上的形状是否应显示在幻灯片上。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回主备注幻灯片的 HeaderFooter 管理器。 |
| [getThemeManager()](#getThemeManager--) | 返回主题管理器。 |
| [getNotesStyle()](#getNotesStyle--) | 返回备注文本的样式。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回主备注幻灯片的绘图参考线集合。 |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定母版幻灯片上的形状是否应显示在幻灯片上。对于母版幻灯片本身此属性始终返回 false。可读写 boolean。

**返回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定母版幻灯片上的形状是否应显示在幻灯片上。对于母版幻灯片本身此属性始终返回 false。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

返回主备注幻灯片的 HeaderFooter 管理器。只读 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**返回：**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

返回主题管理器。只读 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**返回：**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

返回备注文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

返回主备注幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)