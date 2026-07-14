---
title: IImageCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: PPImage 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iimagecollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

PPImage 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 해당 인덱스의 이미지를 반환합니다. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 프레젠테이션에 이미지를 추가합니다. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 스트림에서 프레젠테이션에 이미지를 추가합니다. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 스트림에서 이미지를 생성하고 프레젠테이션에 추가합니다. |
| [addImage(byte[] buffer)](#addImage-byte---) | 지정된 버퍼에서 프레젠테이션에 이미지를 추가합니다. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 다른 프레젠테이션에서 이미지 복사본을 추가합니다. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | SVG 객체에서 프레젠테이션에 이미지를 추가합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

해당 인덱스의 이미지를 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 인덱스. |

**반환값:**
[IPPImage](../../com.aspose.slides/ippimage) - 이미지.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

프레젠테이션에 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 추가할 이미지.

--------------------

이 메서드는 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환한 후 프레젠테이션에 삽입합니다. |

**반환값:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

스트림에서 프레젠테이션에 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지를 추가할 스트림.

--------------------

이 메서드는 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환하지 않고 프레젠테이션에 추가할 수 있습니다. |

**반환값:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

스트림에서 이미지를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지 파일을 추가할 스트림. |
| loadingStreamBehavior | int | 스트림에 적용될 동작. |

**반환값:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

지정된 버퍼에서 프레젠테이션에 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| buffer | byte[] | 버퍼. |

**반환값:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

다른 프레젠테이션에서 이미지 복사본을 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 소스 이미지. |

**반환값:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

SVG 객체에서 프레젠테이션에 이미지를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG 이미지 객체 [ISvgImage](../../com.aspose.slides/isvgimage) |

**반환값:**
[IPPImage](../../com.aspose.slides/ippimage) - 추가된 이미지.