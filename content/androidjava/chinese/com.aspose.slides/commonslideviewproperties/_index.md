---
title: CommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API 参考
description: 表示通用幻灯片视图属性。
type: docs
url: /zh/com.aspose.slides/commonslideviewproperties/
---
**继承:**
java.lang.Object

**实现的所有接口:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

表示通用幻灯片视图属性。

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 设置演示文稿的视图属性
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // 幻灯片视图的缩放值（百分比）
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // 备注视图的缩放值（百分比）
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | Specifies the view scaling ratio in percentages. |
| [setScale(int value)](#setScale-int-) | Specifies the view scaling ratio in percentages. |
| [getVariableScale()](#getVariableScale--) | Specifies that the view content should automatically scale to best fit the current window size. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specifies that the view content should automatically scale to best fit the current window size. |
| [getDrawingGuides()](#getDrawingGuides--) | Returns the collection of the drawing guides. |
### getScale() {#getScale--}
```
public final int getScale()
```

Specifies the view scaling ratio in percentages. Read/write int.

**Returns:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Specifies the view scaling ratio in percentages. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Specifies that the view content should automatically scale to best fit the current window size. Read/write boolean.

**Returns:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Specifies that the view content should automatically scale to best fit the current window size. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()


返回绘图指南的集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)