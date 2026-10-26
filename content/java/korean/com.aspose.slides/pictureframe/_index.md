---
title: PictureFrame
second_title: Aspose.Slides for Java API 레퍼런스
description: 그 안에 그림이 포함된 프레임을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/pictureframe/
---
**상속:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**구현된 모든 인터페이스:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

그 안에 그림이 포함된 프레임을 나타냅니다.

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
>      // 오디오 프레임의 이미지를 설정합니다.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //수정된 프레젠테이션을 디스크에 저장합니다
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | 모양의 잠금을 반환합니다. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | 그림 프레임에 대한 PictureFillFormat 객체를 반환합니다. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 그림 프레임의 높이 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 그림 프레임의 높이 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 그림 프레임의 너비 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 그림 프레임의 너비 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. |
| [isCameo()](#isCameo--) | PictureFrame이 Cameo 객체인지 여부를 확인합니다. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


모양의 잠금을 반환합니다. 읽기 전용 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**반환:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


PictureFrame에 대한 AutoShape 유형을 반환하거나 설정합니다. [ShapeType](../../com.aspose.slides/shapetype) 집합의 허용 가능한 모든 항목이 있으나, 모든 종류의 선은 제외됩니다:

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

**반환:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


PictureFrame에 대한 AutoShape 유형을 반환하거나 설정합니다. [ShapeType](../../com.aspose.slides/shapetype) 집합의 허용 가능한 모든 항목이 있으나, 모든 종류의 선은 제외됩니다:

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


그림 프레임에 대한 PictureFillFormat 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**반환:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


그림 프레임의 높이 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**반환:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


그림 프레임의 높이 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


그림 프레임의 너비 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**반환:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


그림 프레임의 너비 비율(원본 그림 크기에 대한 상대적 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


PictureFrame이 Cameo 객체인지 여부를 확인합니다. 읽기 전용 boolean.

**반환:**
boolean