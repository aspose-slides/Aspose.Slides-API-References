---
title: PictureFrame
second_title: Aspose.Slides for Java API 参考
description: 表示一个内部包含图片的框架。
type: docs
url: /zh/com.aspose.slides/pictureframe/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**所有实现的接口:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)  
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

表示一个包含图片的框架。

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 向幻灯片添加音频帧，指定位置和大小。
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // 向演示文稿资源添加图像。
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // 为音频帧设置图像。
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //保存修改后的演示文稿到磁盘
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | 返回形状的锁定。 |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | 返回图片框的 PictureFillFormat 对象。 |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 返回或设置图片框的高度比例（相对于原始图片大小）。 |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 返回或设置图片框的高度比例（相对于原始图片大小）。 |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 返回或设置图片框的宽度比例（相对于原始图片大小）。 |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 返回或设置图片框的宽度比例（相对于原始图片大小）。 |
| [isCameo()](#isCameo--) | 确定 PictureFrame 是否为 Cameo 对象。 |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

返回形状的锁定。只读 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)。

**返回:**  
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

返回或设置 PictureFrame 的 AutoShape 类型。可使用集合 [ShapeType](../../com.aspose.slides/shapetype) 中的所有项，除所有类型的线之外：

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

读/写 [ShapeType](../../com.aspose.slides/shapetype)。

**返回:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

返回或设置 PictureFrame 的 AutoShape 类型。可使用集合 [ShapeType](../../com.aspose.slides/shapetype) 中的所有项，除所有类型的线之外：

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

读/写 [ShapeType](../../com.aspose.slides/shapetype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

返回图片框的 PictureFillFormat 对象。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

返回或设置图片框的高度比例（相对于原始图片大小）。值 1.0 对应 100%。读/写 float 。

**返回:**  
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

返回或设置图片框的高度比例（相对于原始图片大小）。值 1.0 对应 100%。读/写 float 。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

返回或设置图片框的宽度比例（相对于原始图片大小）。值 1.0 对应 100%。读/写 float 。

**返回:**  
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

返回或设置图片框的宽度比例（相对于原始图片大小）。值 1.0 对应 100%。读/写 float 。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

确定 PictureFrame 是否为 Cameo 对象。只读 boolean。

**返回:**  
boolean