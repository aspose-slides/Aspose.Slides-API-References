---
title: MathBlockFactory
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 블록을 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathblockfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)  
```
public class MathBlockFactory implements IMathBlockFactory
```

수학 블록을 만들 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 수학 블록을 생성합니다 |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 수학 블록을 생성하고 요소를 그 안에 배치합니다 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 수학 블록을 생성하고 요소들을 그 안에 배치합니다 |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```

### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```

수학 블록을 생성합니다

**반환:**  
[IMathBlock](../../com.aspose.slides/imathblock) - 새 수학 블록
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```

수학 블록을 생성하고 요소를 그 안에 배치합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 수학 요소 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 수학 블록
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```

수학 블록을 생성하고 요소들을 그 안에 배치합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 수학 요소들 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 수학 블록