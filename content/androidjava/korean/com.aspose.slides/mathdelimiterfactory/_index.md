---
title: MathDelimiterFactory
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 수학 구분자를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathdelimiterfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathDelimiterFactory](../../com.aspose.slides/imathdelimiterfactory)
```
public class MathDelimiterFactory implements IMathDelimiterFactory
```

수학 구분자를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathDelimiterFactory()](#MathDelimiterFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 요소에 적용하여 수학 구분자를 생성합니다 |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 요소에 적용하여 수학 구분자를 생성합니다 |
### MathDelimiterFactory() {#MathDelimiterFactory--}
```
public MathDelimiterFactory()
```

### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public final IMathDelimiter createMathDelimiter(IMathElement element)
```

요소에 구분자를 적용하여 수학 구분자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 구분자를 적용할 수학 요소 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 새 수학 구분자
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public final IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

요소에 구분자를 적용하여 수학 구분자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 구분자를 적용할 수학 요소들 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 새 수학 구분자