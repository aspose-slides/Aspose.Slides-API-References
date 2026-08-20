---
title: MathFunctionFactory
second_title: Aspose.Slides for Java API 레퍼런스
description: 수학 함수를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathfunctionfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

수학 함수를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


수학 함수를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 함수 이름으로 사용되는 요소 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수 인수로 사용되는 요소 |

**반환값:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 수학 함수
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


수학 함수를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| funcName | java.lang.String | 함수 이름 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수 인수로 사용되는 요소 |

**반환값:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 수학 함수