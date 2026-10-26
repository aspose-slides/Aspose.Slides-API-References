---
title: MathematicalTextFactory
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: MathematicalText 요소를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathematicaltextfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)  
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

MathematicalText 요소를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| Constructor | Description |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## 메서드

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 빈 MathematicalText 요소를 생성합니다 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 지정된 값으로 MathematicalText 요소를 생성합니다 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 지정된 값으로 빈 MathematicalText 요소를 생성합니다 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 지정된 값 및 서식 속성으로 빈 MathematicalText 요소를 생성합니다 |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

빈 MathematicalText 요소를 생성합니다

**반환:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

지정된 값으로 MathematicalText 요소를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathSymbol | char | 텍스트 값으로 사용할 단일 기호 |

**반환:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

지정된 값으로 빈 MathematicalText 요소를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |

**반환:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

지정된 값 및 서식 속성으로 빈 MathematicalText 요소를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 텍스트 서식 설정 |

**반환:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text