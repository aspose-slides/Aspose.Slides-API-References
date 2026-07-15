---
title: IZoomObject
second_title: Aspose.Slides for Android Java API 參考
description: 表示投影片中的 Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/izoomobject/
---
**所有已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

表示投影片中的 Zoom 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getImageType()](#getImageType--) | 取得或設定 Zoom 物件的影像類型。 |
| [setImageType(int value)](#setImageType-int-) | 取得或設定 Zoom 物件的影像類型。 |
| [getReturnToParent()](#getReturnToParent--) | 取得或設定投影片放映中的導覽行為。 |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | 取得或設定投影片放映中的導覽行為。 |
| [getShowBackground()](#getShowBackground--) | 取得或設定指定 Zoom 是否使用目標投影片的背景。 |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | 取得或設定指定 Zoom 是否使用目標投影片的背景。 |
| [getZoomImage()](#getZoomImage--) | 取得或設定 Zoom 物件的影像。 |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | 取得或設定 Zoom 物件的影像。 |
| [getTransitionDuration()](#getTransitionDuration--) | 取得或設定 Zoom 與投影片之間過渡的持續時間。 |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | 取得或設定 Zoom 與投影片之間過渡的持續時間。 |

### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

取得或設定 Zoom 物件的影像類型。可讀寫 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。預設值: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

指定 Zoom 物件是否使用投影片預覽或封面影像。

**傳回值：**
int

### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

取得或設定 Zoom 物件的影像類型。可讀寫 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。預設值: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

指定 Zoom 物件是否使用投影片預覽或封面影像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

取得或設定投影片放映中的導覽行為。可讀寫 boolean。預設值: false

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

屬性的 True 值表示在投影片放映中返回父層的導覽行為。

**傳回值：**
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

取得或設定投影片放映中的導覽行為。可讀寫 boolean。預設值: false

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

屬性的 True 值表示在投影片放映中返回父層的導覽行為。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

取得或設定指定 Zoom 是否使用目標投影片的背景。可讀寫 boolean。預設值: true

--------------------

> ```
> 此範例示範移除 Zoom 物件影像的背景:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回值：**
boolean

### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

取得或設定指定 Zoom 是否使用目標投影片的背景。可讀寫 boolean。預設值: true

--------------------

> ```
> 此範例示範移除 Zoom 物件影像的背景:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

取得或設定 Zoom 物件的影像。可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 此範例示範變更 Zoom 物件的影像:
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


**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

取得或設定 Zoom 物件的影像。可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 此範例示範變更 Zoom 物件的影像:
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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

取得或設定 Zoom 與投影片之間過渡的持續時間。可讀寫 float。預設值: 1.0f

--------------------

> ```
> 此範例示範變更 Zoom 與投影片之間過渡的持續時間:
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

如果未指定 (TransitionDur = 0)，則會使用目標投影片的過渡效果及其相關計時。

**傳回值：**
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

取得或設定 Zoom 與投影片之間過渡的持續時間。可讀寫 float。預設值: 1.0f

--------------------

> ```
> 此範例示範變更 Zoom 與投影片之間過渡的持續時間:
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

如果未指定 (TransitionDur = 0)，則會使用目標投影片的過渡效果及其相關計時。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |