---
title: MathematicalTextFactory
second_title: Aspose.Slides for Java API 참조
description: MathematicalText 요소를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathematicaltextfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

MathematicalText 요소를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 빈 수학 텍스트 요소를 생성합니다 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 지정된 값으로 수학 텍스트 요소를 생성합니다 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 지정된 값으로 빈 수학 텍스트 요소를 생성합니다 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 지정된 값 및 서식 속성으로 빈 수학 텍스트 요소를 생성합니다 |
### MathematicalTextFactory() {#MathematicalTextFactory--}}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}}
```
public final IMathematicalText createMathematicalText()
```

빈 수학 텍스트 요소를 생성합니다

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 새 Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

지정된 값으로 수학 텍스트 요소를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathSymbol | char | 텍스트 값으로 사용할 단일 기호 |

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 새 Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

지정된 값으로 빈 수학 텍스트 요소를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 새 Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

지정된 값 및 서식 속성으로 빈 수학 텍스트 요소를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 텍스트 서식 설정 |

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 새 Mathematical Text