---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 수학 단락을 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

수학 단락을 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 빈 수학 단락 만들기 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 수학 단락을 생성하고 지정된 수학 블록을 그 안에 배치합니다 |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


빈 수학 단락 만들기

**반환:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 새 수학 단락
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


수학 단락을 생성하고 지정된 수학 블록을 그 안에 배치합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 단락에 배치할 수학 블록 |

**반환:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 새 수학 단락