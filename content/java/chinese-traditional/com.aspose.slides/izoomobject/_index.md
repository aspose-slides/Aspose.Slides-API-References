---
title: IZoomObject
second_title: Aspose.Slides for Java API 參考
description: 表示投影片中的 Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/izoomobject/
---
**已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

代表投影片中的 Zoom 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getImageType()](#getImageType--) | 取得或設定 Zoom 物件的影像類型。 |
| [setImageType(int value)](#setImageType-int-) | 取得或設定 Zoom 物件的影像類型。 |
| [getReturnToParent()](#getReturnToParent--) | 取得或設定投影片放映時的導覽行為。 |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | 取得或設定投影片放映時的導覽行為。 |
| [getShowBackground()](#getShowBackground--) | 取得或設定指定 Zoom 是否使用目標投影片背景的值。 |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | 取得或設定指定 Zoom 是否使用目標投影片背景的值。 |
| [getZoomImage()](#getZoomImage--) | 取得或設定 Zoom 物件的影像。 |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | 取得或設定 Zoom 物件的影像。 |
| [getTransitionDuration()](#getTransitionDuration--) | 取得或設定 Zoom 與投影片之間的過渡持續時間。 |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | 取得或設定 Zoom 與投影片之間的過渡持續時間。 |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


取得或設定 Zoom 物件的影像類型。讀寫 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。預設值：Preview

--------------------

> ```
> 此範例示範將 Image Type 變更為 Preview 值。 
>  在此情況下，Zoom 物件的目前影像會變更為投影片影像：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 55, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

指定 Zoom 物件是否使用投影片預覽或封面圖像。

**回傳值：**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


取得或設定 Zoom 物件的影像類型。讀寫 [ZoomImageType](../../com.aspose.slides/zoomimagetype)。預設值：Preview

--------------------

> ```
> 此範例示範將 Image Type 變更為 Preview 值。 
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

指定 Zoom 物件是否使用投影片預覽或封面圖像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


取得或設定投影片放映時的導覽行為。讀寫 boolean。預設值：false

--------------------

> ```
> 範例:
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

屬性的 True 值表示投影片放映時返回父項的導覽行為。

**回傳值：**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


取得或設定投影片放映時的導覽行為。讀寫 boolean。預設值：false

--------------------

> ```
> 範例:
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

屬性的 True 值表示投影片放映時返回父項的導覽行為。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


取得或設定指定 Zoom 是否使用目標投影片背景的值。讀寫 boolean。預設值：true

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

**回傳值：**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```


取得或設定指定 Zoom 是否使用目標投影片背景的值。讀寫 boolean。預設值：true

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


取得或設定 Zoom 物件的影像。讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 此範例示範變更 Zoom 物件的影像：
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

**回傳值：**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```


取得或設定 Zoom 物件的影像。讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> 此範例示範變更 Zoom 物件的影像：
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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```


取得或設定 Zoom 與投影片之間的過渡持續時間。讀寫 float。預設值：1.0f

--------------------

> ```
> 此範例示範變更 Zoom 與投影片之間過渡的持續時間：
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

如果未指定 (TransitionDur = 0)，將使用目標投影片的過渡效果及其相關的計時設定。

**回傳值：**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


取得或設定 Zoom 與投影片之間的過渡持續時間。讀寫 float。預設值：1.0f

--------------------

> ```
> 此範例示範變更 Zoom 與投影片之間過渡的持續時間：
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

如果未指定 (TransitionDur = 0)，將使用目標投影片的過渡效果及其相關的計時設定。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |