---
title: IPictureFillFormatEffectiveData
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: 그림 채우기 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ipicturefillformateffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

그림 채우기 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDpi()](#getDpi--) | 그림을 채우는 데 사용되는 dpi를 반환합니다. |
| [getPictureFillMode()](#getPictureFillMode--) | 그림 채우기 모드를 반환합니다. |
| [getPicture()](#getPicture--) | 그림을 반환합니다. |
| [getCropLeft()](#getCropLeft--) | 그림의 왼쪽에서 잘려 나간 실제 이미지 너비의 백분율을 반환합니다. |
| [getCropTop()](#getCropTop--) | 그림의 상단에서 잘려 나간 실제 이미지 높이의 백분율을 반환합니다. |
| [getCropRight()](#getCropRight--) | 그림의 오른쪽에서 잘려 나간 실제 이미지 너비의 백분율을 반환합니다. |
| [getCropBottom()](#getCropBottom--) | 그림의 하단에서 잘려 나간 실제 이미지 높이의 백분율을 반환합니다. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


그림을 채우는 데 사용되는 dpi를 반환합니다. 읽기 전용 int.

**반환:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


그림 채우기 모드를 반환합니다. 읽기 전용 [PictureFillMode](../../com.aspose.slides/picturefillmode).

**반환:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


그림을 반환합니다. 읽기 전용 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**반환:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


그림의 왼쪽에서 잘려 나간 실제 이미지 너비의 백분율을 반환합니다. 읽기 전용 float.

**반환:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


그림의 상단에서 잘려 나간 실제 이미지 높이의 백분율을 반환합니다. 읽기 전용 float.

**반환:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


그림의 오른쪽에서 잘려 나간 실제 이미지 너비의 백분율을 반환합니다. 읽기 전용 float.

**반환:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


그림의 하단에서 잘려 나간 실제 이미지 높이의 백분율을 반환합니다. 읽기 전용 float.

**반환:**
float