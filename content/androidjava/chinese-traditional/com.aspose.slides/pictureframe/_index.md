---
title: PictureFrame
second_title: Aspose.Slides for Android Java API 參考
description: 表示一個內含圖片的框架。
type: docs
url: /zh-hant/com.aspose.slides/pictureframe/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**全部實作的介面：**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

表示一個內含圖片的框架。

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 在投影片上新增一個音訊框架，並指定位置與大小。
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // 將圖片新增至簡報資源。
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // 設定音訊框架的圖片。
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //將修改後的簡報儲存至磁碟
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | 返回形狀的鎖。 |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | 返回圖片框架的 PictureFillFormat 物件。 |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 返回或設定圖片框架的高度比例（相對於原始圖片大小）。 |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 返回或設定圖片框架的高度比例（相對於原始圖片大小）。 |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 返回或設定圖片框架的寬度比例（相對於原始圖片大小）。 |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 返回或設定圖片框架的寬度比例（相對於原始圖片大小）。 |
| [isCameo()](#isCameo--) | 判斷 PictureFrame 是否為 Cameo 物件。 |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

返回形狀的鎖。唯讀 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)。

**返回值:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

返回或設定 PictureFrame 的 AutoShape 類型。允許使用集合 [ShapeType](../../com.aspose.slides/shapetype) 中的所有項目，除所有線條類型外：

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

可讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**返回值:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

返回或設定 PictureFrame 的 AutoShape 類型。允許使用集合 [ShapeType](../../com.aspose.slides/shapetype) 中的所有項目，除所有線條類型外：

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

可讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

返回圖片框架的 PictureFillFormat 物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回值:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

返回或設定圖片框架的高度比例（相對於原始圖片大小）。值 1.0 對應 100%。可讀寫 float 。

**返回值:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

返回或設定圖片框架的高度比例（相對於原始圖片大小）。值 1.0 對應 100%。可讀寫 float 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

返回或設定圖片框架的寬度比例（相對於原始圖片大小）。值 1.0 對應 100%。可讀寫 float 。

**返回值:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

返回或設定圖片框架的寬度比例（相對於原始圖片大小）。值 1.0 對應 100%。可讀寫 float 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

判斷 PictureFrame 是否為 Cameo 物件。唯讀 boolean。

**返回值:**
boolean