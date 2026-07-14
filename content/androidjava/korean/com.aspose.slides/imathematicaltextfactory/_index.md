---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: MathematicalText 요소를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

MathematicalText 요소를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 빈 수학 텍스트 요소를 생성합니다 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 지정된 값을 사용하여 수학 텍스트 요소를 생성합니다 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 지정된 값을 사용하여 빈 수학 텍스트 요소를 생성합니다 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 지정된 값과 서식 속성을 사용하여 빈 수학 텍스트 요소를 생성합니다 |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

빈 수학 텍스트 요소를 생성합니다

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

지정된 값을 사용하여 수학 텍스트 요소를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathSymbol | char | 텍스트 값으로 사용할 단일 기호 |

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

지정된 값을 사용하여 빈 수학 텍스트 요소를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

지정된 값과 서식 속성을 사용하여 빈 수학 텍스트 요소를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 텍스트 서식 설정 |

**반환값:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text