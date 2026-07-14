---
title: MathParagraphFactory
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 수학 단락을 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathparagraphfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

수학 단락을 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 빈 수학 단락을 생성합니다 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 수학 단락을 생성하고 지정된 수학 블록을 배치합니다 |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


빈 수학 단락을 생성합니다

**반환값:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 새 수학 단락
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


수학 단락을 생성하고 지정된 수학 블록을 배치합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 단락에 배치할 수학 블록 |

**반환값:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 새 수학 단락