---
title: MathArrayFactory
second_title: Android용 Aspose.Slides Java API 참조
description: 수학 배열을 만들 수 있습니다
type: docs
url: /ko/com.aspose.slides/matharrayfactory/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathArrayFactory](../../com.aspose.slides/imatharrayfactory)  
```
public class MathArrayFactory implements IMathArrayFactory
```

수학 배열을 만들 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathArrayFactory()](#MathArrayFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Creates a math array and places the specified element in it |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Creates a math array and places specified elements in it |
### MathArrayFactory() {#MathArrayFactory--}
```
public MathArrayFactory()
```

### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public final IMathArray createMathArray(IMathElement element)
```

수학 배열을 만들고 지정된 요소를 배열에 배치합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 배열에 배치할 수학 요소 |

**반환값:**
[IMathArray](../../com.aspose.slides/imatharray) - 새 수학 배열
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public final IMathArray createMathArray(IMathElementCollection elements)
```

수학 배열을 만들고 지정된 요소들을 배열에 배치합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 배열에 배치할 수학 요소들 |

**반환값:**
[IMathArray](../../com.aspose.slides/imatharray) - 새 수학 배열