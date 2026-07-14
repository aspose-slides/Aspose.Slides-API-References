---
title: PictureFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 그 안에 picture가 포함된 프레임을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/pictureframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

picture가 포함된 프레임을 나타냅니다.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 지정된 위치와 크기로 슬라이드에 오디오 프레임을 추가합니다.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // 프레젠테이션 리소스에 이미지를 추가합니다.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // 오디오 프레임에 이미지를 설정합니다.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //수정된 프레젠테이션을 디스크에 저장합니다
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## 메서드

| Method | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | shape의 잠금을 반환합니다. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | picture 프레임에 대한 PictureFillFormat 객체를 반환합니다. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | picture 프레임의 높이 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | picture 프레임의 높이 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | picture 프레임의 너비 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | picture 프레임의 너비 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. |
| [isCameo()](#isCameo--) | PictureFrame이 Cameo 객체인지 여부를 결정합니다. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

shape의 잠금을 반환합니다. 읽기 전용 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Returns:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

PictureFrame에 대한 AutoShape 유형을 반환하거나 설정합니다. 허용되는 모든 항목은 [ShapeType](../../com.aspose.slides/shapetype)에 포함되며, 다음과 같은 모든 라인은 제외됩니다:

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

읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

PictureFrame에 대한 AutoShape 유형을 반환하거나 설정합니다. 허용되는 모든 항목은 [ShapeType](../../com.aspose.slides/shapetype)에 포함되며, 다음과 같은 모든 라인은 제외됩니다:

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

읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

picture 프레임에 대한 PictureFillFormat 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

picture 프레임의 높이 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**Returns:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

picture 프레임의 높이 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

picture 프레임의 너비 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**Returns:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

picture 프레임의 너비 비율(원본 picture 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

PictureFrame이 Cameo 객체인지 여부를 결정합니다. 읽기 전용 boolean.

**Returns:**
boolean