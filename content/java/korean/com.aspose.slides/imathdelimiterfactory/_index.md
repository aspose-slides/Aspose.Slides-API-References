---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: 수학 구분자를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

수학 구분자를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 요소에 적용하여 수학 구분자를 생성합니다 |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 요소에 적용하여 수학 구분자를 생성합니다 |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

요소에 적용하여 수학 구분자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 델리미터를 적용할 수학 요소 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 새 수학 구분자
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

요소에 적용하여 수학 구분자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 델리미터를 적용할 수학 요소들 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 새 수학 구분자