---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
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
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 수학 블록을 생성하고 요소를 그 안에 배치합니다 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 수학 블록을 생성하고 여러 요소를 그 안에 배치합니다 |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

수학 블록을 생성합니다

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 MathBlock
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

수학 블록을 생성하고 해당 요소를 그 안에 배치합니다

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 수학 요소 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 MathBlock
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

수학 블록을 생성하고 요소들을 그 안에 배치합니다

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 수학 요소들 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 새 MathBlock