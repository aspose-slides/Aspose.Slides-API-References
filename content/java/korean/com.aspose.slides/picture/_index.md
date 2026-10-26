---
title: Picture
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션의 그림을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/picture/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)  
```
public final class Picture implements IPVIObject, ISlidesPicture
```

프레젠테이션의 그림을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | 내장 이미지를 반환하거나 설정합니다. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 내장 이미지를 반환하거나 설정합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | 연결된 이미지 URL을 반환하거나 설정합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 연결된 이미지 URL을 반환하거나 설정합니다. |
| [getImageTransform()](#getImageTransform--) | 이미지 변환 효과 컬렉션을 반환합니다. |
| [getPresentation()](#getPresentation--) | 프레젠테이션을 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체와 비교합니다. |
| [hashCode()](#hashCode--) | 해시를 반환합니다. |
| [getSlide()](#getSlide--) | 그림의 상위 슬라이드를 반환합니다. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent 상위 객체를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

내장 이미지를 반환하거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

**반환:**  
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

내장 이미지를 반환하거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

연결된 이미지 URL을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

연결된 이미지 URL을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

이미지 변환 효과 컬렉션을 반환합니다. 읽기 전용 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**반환:**  
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 객체와 비교합니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 객체. |

**반환:**  
boolean - 객체가 동일하면 True, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

해시를 반환합니다.

**반환:**  
int - 해시.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

그림의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)