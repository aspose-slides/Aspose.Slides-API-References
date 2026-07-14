---
title: VideoPlayerHtmlController
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 이 클래스는 비디오 및 오디오 파일을 HTML로 내보낼 수 있습니다.
type: docs
url: /ko/com.aspose.slides/videoplayerhtmlcontroller/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

이 클래스는 비디오 및 오디오 파일을 HTML로 내보낼 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | 새 컨트롤러 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |

### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```

새 컨트롤러 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 비디오 및 오디오 파일이 생성될 경로 |
| fileName | java.lang.String | HTML 파일 이름 |
| baseUri | java.lang.String | 링크 생성에 사용할 기본 URI |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML 문서 헤더를 기록합니다. 프레젠테이션 변환당 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML 문서 푸터를 기록합니다. 프레젠테이션 변환당 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML 슬라이드 헤더를 기록합니다. 각 슬라이드마다 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML 슬라이드 푸터를 기록합니다. 각 슬라이드마다 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

모양 렌더링 전에 호출됩니다. 각 모양마다 한 번 호출됩니다. 이 함수가 generator에 내용을 기록하면 현재 슬라이드 이미지 생성이 종료되고, 추가된 HTML 조각이 삽입된 뒤 새로운 이미지가 이전 이미지 위에 시작됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

모양 렌더링 전에 호출됩니다. 각 모양마다 한 번 호출됩니다. 이 함수가 generator에 내용을 기록하면 현재 슬라이드 이미지 생성이 종료되고, 추가된 HTML 조각이 삽입된 뒤 새로운 이미지가 이전 이미지 위에 시작됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```

SVG로 렌더링하기 전에 호출되어 사용자가 결과 SVG를 제어할 수 있게 합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

객체가 저장되어야 할 위치를 결정합니다. 이 메서드는 각 객체 ID마다 한 번 호출됩니다. 동일한 데이터, semanticName 및 contentType을 가진 두 객체가 서로 다른 ID를 가질 수 있음은 보장되지 않습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**반환값:**
int

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```

외부 객체에 대한 URL을 반환합니다. 이 메서드는 \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 가 [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) 를 반환했을 때 항상 호출되며, 임베딩이 불가능할 경우 [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) 를 반환했을 때도 호출될 수 있습니다. 동일한 객체 ID에 대해 여러 번 호출될 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**반환값:**
java.lang.String

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```

외부 객체를 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |