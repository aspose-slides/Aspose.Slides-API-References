---
title: IMathBarFactory
second_title: Aspose.Slides Android용 Java API 참조
description: 수학 바를 생성할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

수학 바를 생성할 수 있습니다.

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 요소에 적용하여 수학 바를 생성합니다 |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 요소에 적용하여 수학 바를 생성합니다 |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

요소에 적용하여 수학 바를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바를 적용할 수학 요소 |

**반환값:**
[IMathBar](../../com.aspose.slides/imathbar) - 새로운 수학 바 요소
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

요소에 적용하여 수학 바를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바를 적용할 수학 요소 |
| position | int | 바의 위치 |

**반환값:**
[IMathBar](../../com.aspose.slides/imathbar) - 새로운 수학 바 요소