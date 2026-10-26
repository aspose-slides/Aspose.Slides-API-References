---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /ko/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

수학 블록을 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 수학 블록을 생성합니다 |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 수학 블록을 생성하고 요소를 배치합니다 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 수학 블록을 생성하고 요소들을 배치합니다 |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

수학 블록을 생성합니다

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 수학 블록
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

수학 블록을 생성하고 요소를 배치합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 수학 요소 |

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 수학 블록
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

수학 블록을 생성하고 요소들을 배치합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 수학 요소들 |

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 수학 블록