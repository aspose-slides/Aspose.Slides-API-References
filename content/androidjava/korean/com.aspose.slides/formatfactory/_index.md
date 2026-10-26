---
title: FormatFactory
second_title: Aspose.Slides for Android용 Java API 참조
description: COM 인터페이스를 통해 포맷을 생성할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/formatfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

COM 인터페이스를 통해 포맷을 생성할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInstance()](#getInstance--) | 포맷 팩터리 정적 인스턴스. |
| [createPortionFormat()](#createPortionFormat--) | 새 [IPortionFormat](../../com.aspose.slides/iportionformat)를 생성합니다. |
| [createParagraphFormat()](#createParagraphFormat--) | 새 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)를 생성합니다. |
| [createTextFrameFormat()](#createTextFrameFormat--) | 새 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)를 생성합니다. |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

포맷 팩터리 정적 인스턴스. 읽기 전용 [FormatFactory](../../com.aspose.slides/formatfactory).

**반환값:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

새 [IPortionFormat](../../com.aspose.slides/iportionformat)를 생성합니다.

**반환값:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - 새 포션 포맷.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

새 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)를 생성합니다.

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 새 단락 포맷.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

새 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)를 생성합니다.

**반환값:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 새 텍스트 프레임 포맷.