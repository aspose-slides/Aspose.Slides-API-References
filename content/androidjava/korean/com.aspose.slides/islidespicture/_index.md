---
title: ISlidesPicture
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션의 그림을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/islidespicture/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

프레젠테이션의 그림을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getImage()](#getImage--) | 내장 이미지를 반환하거나 설정합니다. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 내장 이미지를 반환하거나 설정합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | 연결된 이미지의 URL을 반환하거나 설정합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 연결된 이미지의 URL을 반환하거나 설정합니다. |
| [getImageTransform()](#getImageTransform--) | 이미지 변환 효과의 컬렉션을 반환합니다. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


내장 이미지를 반환하거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

**반환:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


내장 이미지를 반환하거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


연결된 이미지의 URL을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


연결된 이미지의 URL을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


이미지 변환 효과의 컬렉션을 반환합니다. 읽기 전용 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**반환:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)