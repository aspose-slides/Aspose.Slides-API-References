---
title: PictureFrame
second_title: Aspose.Slides for Java API 參考文件
description: 表示內部含有圖片的框架。
type: docs
url: /zh-hant/com.aspose.slides/pictureframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

表示內部含有圖片的框架。

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 在投影片上新增音訊框，並指定位置與大小。
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // 将影像新增至簡報資源。
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // 設定音訊框的圖片。
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //將已修改的簡報儲存至磁碟
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | 返回形狀的鎖定。 |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | 返回 picture frame 的 PictureFillFormat 物件。 |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 返回或設定圖片框架的高度縮放比例（相對於原始圖片尺寸）。 |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 返回或設定圖片框架的高度縮放比例（相對於原始圖片尺寸）。 |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 返回或設定圖片框架的寬度縮放比例（相對於原始圖片尺寸）。 |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 返回或設定圖片框架的寬度縮放比例（相對於原始圖片尺寸）。 |
| [isCameo()](#isCameo--) | 判斷 PictureFrame 是否為 Cameo 物件。 |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


返回形狀的鎖定。唯讀 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)。

**返回：**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


返回或設定 PictureFrame 的 AutoShape 類型。允許的集合項目為 [ShapeType](../../com.aspose.slides/shapetype)，除所有線條外：

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

**返回：**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


返回或設定 PictureFrame 的 AutoShape 類型。允許的集合項目為 [ShapeType](../../com.aspose.slides/shapetype)，除所有線條外：

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


返回 picture frame 的 PictureFillFormat 物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


返回或設定圖片框架的高度縮放比例（相對於原始圖片尺寸）。值 1.0 對應 100%。可讀寫 float 。

**返回：**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


返回或設定圖片框架的高度縮放比例（相對於原始圖片尺寸）。值 1.0 對應 100%。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


返回或設定圖片框架的寬度縮放比例（相對於原始圖片尺寸）。值 1.0 對應 100%。可讀寫 float 。

**返回：**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


返回或設定圖片框架的寬度縮放比例（相對於原始圖片尺寸）。值 1.0 對應 100%。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


判斷 PictureFrame 是否為 Cameo 物件。唯讀 boolean。

**返回：**
boolean