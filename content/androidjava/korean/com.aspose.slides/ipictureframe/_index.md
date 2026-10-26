---
title: IPictureFrame
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 그 안에 그림이 포함된 프레임을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipictureframe/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

그 안에 그림이 포함된 프레임을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | PictureFrame의 잠금을 반환합니다. |
| [getPictureFormat()](#getPictureFormat--) | 그림 프레임에 대한 PictureFillFormat 객체를 반환합니다. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 그림 프레임의 높이 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 그림 프레임의 높이 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 그림 프레임의 너비 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 그림 프레임의 너비 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

PictureFrame의 잠금을 반환합니다. 읽기 전용 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**반환값:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

그림 프레임에 대한 PictureFillFormat 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**반환값:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

그림 프레임의 높이 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 float.

**반환값:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

그림 프레임의 높이 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

그림 프레임의 너비 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 float.

**반환값:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

그림 프레임의 너비 비율(원본 그림 크기에 대한)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |