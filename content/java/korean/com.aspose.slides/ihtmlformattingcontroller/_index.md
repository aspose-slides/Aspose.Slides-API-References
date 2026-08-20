---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: HTML 파일 생성을 제어합니다.
type: docs
url: /ko/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

HTML 파일 생성을 제어합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML 문서 헤더를 작성하기 위해 호출됩니다. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML 문서 푸터를 작성하기 위해 호출됩니다. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML 슬라이드 헤더를 작성하기 위해 호출됩니다. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML 슬라이드 푸터를 작성하기 위해 호출됩니다. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | shape의 렌더링 전에 호출됩니다. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | shape의 렌더링 전에 호출됩니다. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML 문서 헤더를 작성하기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 현재 렌더링 중인 Presentation. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML 문서 푸터를 작성하기 위해 호출됩니다. 프레젠테이션 변환당 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 현재 렌더링 중인 Presentation. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML 슬라이드 헤더를 작성하기 위해 호출됩니다. 각 슬라이드마다 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| slide | [ISlide](../../com.aspose.slides/islide) | 현재 렌더링 중인 Slide. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML 슬라이드 푸터를 작성하기 위해 호출됩니다. 각 슬라이드마다 한 번 호출됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| slide | [ISlide](../../com.aspose.slides/islide) | 현재 렌더링 중인 Slide. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

shape의 렌더링 전에 호출됩니다. 각 shape마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 기록하면 현재 슬라이드 이미지 생성이 완료되고, 추가된 HTML 조각이 삽입되며, 새로운 이미지가 이전 이미지 위에 시작됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| shape | [IShape](../../com.aspose.slides/ishape) | 렌더링될 예정인 Shape. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

shape의 렌더링 전에 호출됩니다. 각 shape마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 기록하면 현재 슬라이드 이미지 생성이 완료되고, 추가된 HTML 조각이 삽입되며, 새로운 이미지가 이전 이미지 위에 시작됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 출력 객체. |
| shape | [IShape](../../com.aspose.slides/ishape) | 마지막으로 렌더링된 Shape. |