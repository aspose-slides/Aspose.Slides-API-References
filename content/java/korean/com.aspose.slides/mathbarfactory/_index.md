---
title: MathBarFactory
second_title: Aspose.Slides for Java API 레퍼런스
description: 수학 바를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathbarfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

수학 바를 만들 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 요소에 적용하여 수학 바를 생성합니다 |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 요소에 적용하여 수학 바를 생성합니다 |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```

### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```

요소에 적용하여 수학 바를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바를 적용할 수학 요소 |

**반환:**
[IMathBar](../../com.aspose.slides/imathbar) - 새 수학 바 요소
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```

요소에 적용하여 수학 바를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바를 적용할 수학 요소 |
| position | int | 바의 위치 |

**반환:**
[IMathBar](../../com.aspose.slides/imathbar) - 새 수학 바 요소