---
title: EmbedAllFontsHtmlController
second_title: Java용 Aspose.Slides API 참조
description: WOFF 형식으로 모든 프레젠테이션 글꼴을 포함하기 위해 사용할 포맷팅 컨트롤러 클래스입니다.
type: docs
url: /ko/com.aspose.slides/embedallfontshtmlcontroller/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

WOFF 형식으로 모든 프레젠테이션 글꼴을 포함하기 위해 사용할 포맷팅 컨트롤러 클래스입니다.

## 생성자

| Constructor | Description |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | 새 인스턴스를 생성합니다. |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | 새 인스턴스를 생성합니다. |

## 메서드

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML 문서 헤더를 쓰기 위해 호출됩니다. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML 문서 푸터를 쓰기 위해 호출됩니다. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML 슬라이드 헤더를 쓰기 위해 호출됩니다. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML 슬라이드 푸터를 쓰기 위해 호출됩니다. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 쉐이프 렌더링 전에 호출됩니다. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 쉐이프 렌더링 전에 호출됩니다. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | [Presentation](../../com.aspose.slides/presentation)에 포함된 모든 글꼴을 씁니다. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | 데이터를 base64로 인코딩하여 HTML 문서 자체에 씁니다. |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

새 인스턴스를 생성합니다.

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

새 인스턴스를 생성합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | 포함에서 제외할 글꼴 |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML 문서 헤더를 쓰기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 현재 렌더링 중인 프레젠테이션. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML 문서 푸터를 쓰기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 현재 렌더링 중인 프레젠테이션. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML 슬라이드 헤더를 쓰기 위해 호출됩니다. 각 슬라이드마다 한 번 호출됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| slide | [ISlide](../../com.aspose.slides/islide) | 현재 렌더링 중인 슬라이드. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML 슬라이드 푸터를 쓰기 위해 호출됩니다. 각 슬라이드마다 한 번 호출됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| slide | [ISlide](../../com.aspose.slides/islide) | 현재 렌더링 중인 슬라이드. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

쉐이프 렌더링 전에 호출됩니다. 각 쉐이프마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 종료되고, 추가된 HTML 조각이 삽입된 뒤 새로운 이미지가 이전 이미지 위에 시작됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| shape | [IShape](../../com.aspose.slides/ishape) | 렌더링될 쉐이프. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

쉐이프 렌더링 전에 호출됩니다. 각 쉐이프마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 종료되고, 추가된 HTML 조각이 삽입된 뒤 새로운 이미지가 이전 이미지 위에 시작됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| shape | [IShape](../../com.aspose.slides/ishape) | 마지막으로 렌더링된 쉐이프. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

[Presentation](../../com.aspose.slides/presentation)에 포함된 모든 글꼴을 씁니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 현재 렌더링 중인 프레젠테이션. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

데이터를 base64로 인코딩하여 HTML 문서 자체에 씁니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML 생성기 |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | 직렬화할 글꼴 |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | 대체된 글꼴(글꼴 대체가 발생한 경우), 그렇지 않으면 null |
| fontStyle | java.lang.String | 글꼴 스타일 |
| fontWeight | java.lang.String | 글꼴 두께 |
| fontData | byte[] | 글꼴 데이터 |