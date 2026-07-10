---
title: ZoomObject
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片中的 Zoom 对象。
type: docs
url: /zh/com.aspose.slides/zoomobject/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有实现的接口：**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

表示幻灯片中的 Zoom 对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImageType()](#getImageType--) | 获取或设置 Zoom 对象的图像类型。 |
| [setImageType(int value)](#setImageType-int-) | 获取或设置 Zoom 对象的图像类型。 |
| [getReturnToParent()](#getReturnToParent--) | 获取或设置幻灯片放映中的导航行为。 |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | 获取或设置幻灯片放映中的导航行为。 |
| [getShowBackground()](#getShowBackground--) | 获取或设置指定 Zoom 是否使用目标幻灯片背景的值。 |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | 获取或设置指定 Zoom 是否使用目标幻灯片背景的值。 |
| [getZoomImage()](#getZoomImage--) | 获取或设置 Zoom 对象的图像。 |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | 获取或设置 Zoom 对象的图像。 |
| [getTransitionDuration()](#getTransitionDuration--) | 获取或设置 Zoom 与幻灯片之间过渡的持续时间。 |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | 获取或设置 Zoom 与幻灯片之间过渡的持续时间。 |
### getImageType() {#getImageType--}
```
public final int getImageType()
```


获取或设置 Zoom 对象的图像类型。读/写 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。默认值：Preview

--------------------

> ```
> 下一示例演示将图像类型更改为 Preview 值。 
>  在此情况下，Zoom 对象的当前图像会更改为幻灯片图像：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public final void setImageType(int value)
```


Gets or sets the image type of a zoom object. Read/write [ZoomImageType](../../com.aspose.slides/zoomimagetype). Default value: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Specifies whether the Zoom object is using the slide preview or a cover image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

获取或设置幻灯片放映中的导航行为。读/写 boolean。默认值：false

--------------------

> ```
> 示例：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

属性的 true 值指定幻灯片放映中的返回父级导航行为。

**Returns:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

获取或设置幻灯片放映中的导航行为。读/写 boolean。默认值：false

--------------------

> ```
> 示例：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

属性的 true 值指定幻灯片放映中的返回父级导航行为。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

获取或设置指定 Zoom 是否使用目标幻灯片背景的值。读/写 boolean。默认值：true

--------------------

> ```
> 示例演示如何移除 Zoom 对象图像的背景：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

获取或设置指定 Zoom 是否使用目标幻灯片背景的值。读/写 boolean。默认值：true

--------------------

> ```
> 示例演示如何移除 Zoom 对象图像的背景：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```
Gets or sets image for zoom object. Read/write [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> 示例演示更改 Zoom 对象的图像：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Gets or sets image for zoom object. Read/write [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

获取或设置 Zoom 与幻灯片之间过渡的持续时间。读/写 float。默认值：1.0f

--------------------

> ```
> 示例演示更改 Zoom 与幻灯片之间过渡的持续时间：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

如果未指定 (TransitionDur = 0)，则将使用目标幻灯片的过渡以及与该过渡关联的时间设置。

**Returns:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)


获取或设置 Zoom 与幻灯片之间过渡的持续时间。读/写 float。默认值：1.0f

--------------------

> ```
> 示例演示了如何更改 Zoom 与幻灯片之间过渡的持续时间：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

如果未指定 (TransitionDur = 0)，则将使用目标幻灯片的过渡以及与该过渡关联的时间设置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |