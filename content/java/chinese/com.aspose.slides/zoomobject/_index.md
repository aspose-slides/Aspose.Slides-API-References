---
title: ZoomObject
second_title: Aspose.Slides for Java API 参考
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
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

指定 Zoom 对象是使用幻灯片预览还是封面图像。

**返回：**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

获取或设置 Zoom 对象的图像类型。读/写 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。默认值：Preview

--------------------

> ```
> 下一个示例演示将 Image Type 更改为 Preview 值。 
>  在这种情况下，Zoom 对象的当前图像会更改为幻灯片图像:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

指定 Zoom 对象是使用幻灯片预览还是封面图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

获取或设置幻灯片放映中的导航行为。读/写 boolean。默认值：false

--------------------

> ```
> Example:
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

属性的 true 值表示在幻灯片放映中返回父级的导航行为。

**返回：**
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

属性的 true 值表示在幻灯片放映中返回父级的导航行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

获取或设置指定 Zoom 是否使用目标幻灯片背景的值。读/写 boolean。默认值：true

--------------------

> ```
> 示例演示移除 Zoom 对象图像的背景：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

获取或设置指定 Zoom 是否使用目标幻灯片背景的值。读/写 boolean。默认值：true

--------------------

> ```
> 示例演示移除 Zoom 对象图像的背景:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

获取或设置 Zoom 对象的图像。读/写 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 示例演示更改 Zoom 对象的图像:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

获取或设置 Zoom 对象的图像。读/写 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 示例演示更改 Zoom 对象的图像:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
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

如果未指定（TransitionDur = 0），将使用目标幻灯片的过渡及其相关时间。

**返回：**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
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

如果未指定（TransitionDur = 0），将使用目标幻灯片的过渡及其相关时间。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |