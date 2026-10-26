---
title: ZoomObject
second_title: Aspose.Slides for Java API 參考
description: 表示投影片中的 Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/zoomobject/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有已實作的介面:**  
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)  
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

表示投影片中的 Zoom 物件。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getImageType()](#getImageType--) | 取得或設定 Zoom 物件的影像類型。 |
| [setImageType(int value)](#setImageType-int-) | 取得或設定 Zoom 物件的影像類型。 |
| [getReturnToParent()](#getReturnToParent--) | 取得或設定投影片放映時的導覽行為。 |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | 取得或設定投影片放映時的導覽行為。 |
| [getShowBackground()](#getShowBackground--) | 取得或設定指定 Zoom 是否使用目的投影片背景的值。 |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | 取得或設定指定 Zoom 是否使用目的投影片背景的值。 |
| [getZoomImage()](#getZoomImage--) | 取得或設定 Zoom 物件的影像。 |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | 取得或設定 Zoom 物件的影像。 |
| [getTransitionDuration()](#getTransitionDuration--) | 取得或設定 Zoom 與投影片之間過渡的持續時間。 |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | 取得或設定 Zoom 與投影片之間過渡的持續時間。 |

### getImageType() {#getImageType--}
```
public final int getImageType()
```

取得或設定 Zoom 物件的影像類型。讀/寫 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。預設值：Preview

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

指定 Zoom 物件是否使用投影片預覽或封面影像。

**傳回值:**
int

### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

取得或設定 Zoom 物件的影像類型。讀/寫 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。預設值：Preview

--------------------

> ```
> 下一個範例示範將影像類型變更為 Preview 值。 
>  在此情況下，Zoom 物件的目前影像會變更為投影片影像：
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

指定 Zoom 物件是否使用投影片預覽或封面影像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

取得或設定投影片放映時的導覽行為。讀/寫 boolean。預設值：false

--------------------

> ```
> 範例：
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

屬性為 true 時，表示在投影片放映中返回父層的導覽行為。

**傳回值:**
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

取得或設定投影片放映時的導覽行為。讀/寫 boolean。預設值：false

--------------------

> ```
> 範例：
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

屬性為 true 時，表示在投影片放映中返回父層的導覽行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

取得或設定指定 Zoom 是否使用目的投影片背景的值。讀/寫 boolean。預設值：true

--------------------

> ```
> 範例說明如何移除 Zoom 物件影像的背景：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回值:**
boolean

### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

取得或設定指定 Zoom 是否使用目的投影片背景的值。讀/寫 boolean。預設值：true

--------------------

> ```
> 範例說明如何移除 Zoom 物件影像的背景：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

取得或設定 Zoom 物件的影像。讀/寫 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 範例說明更改 Zoom 物件的影像：
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


**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

取得或設定 Zoom 物件的影像。讀/寫 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 範例說明更改 Zoom 物件的影像：
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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

取得或設定 Zoom 與投影片之間過渡的持續時間。讀/寫 float。預設值：1.0f

--------------------

> ```
> 範例說明變更 Zoom 與投影片之間過渡的持續時間：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


如果未指定 (TransitionDur = 0)，則會使用目的投影片的過渡以及與該過渡相關的時間設定。

**傳回值:**
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

取得或設定 Zoom 與投影片之間過渡的持續時間。讀/寫 float。預設值：1.0f

--------------------

> ```
> 範例說明變更 Zoom 與投影片之間過渡的持續時間：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


如果未指定 (TransitionDur = 0)，則會使用目的投影片的過渡以及與該過渡相關的時間設定。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |