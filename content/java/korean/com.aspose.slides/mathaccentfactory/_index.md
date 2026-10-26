---
title: MathAccentFactory
second_title: Aspose.Slides for Java API 참조
description: 수학 악센트를 생성하도록 허용합니다
type: docs
url: /ko/com.aspose.slides/mathaccentfactory/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)  
```
public class MathAccentFactory implements IMathAccentFactory
```

MathAccent를 생성하도록 허용합니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 기본 악센트 문자 값을 사용하여 지정된 수학 요소에 적용되는 MathAccent를 생성합니다 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 지정된 수학 요소에 적용되는 MathAccent를 생성합니다 |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

지정된 수학 요소에 적용되는 MathAccent를 기본 악센트 문자 값으로 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |

**반환값:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새로운 MathAccent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

지정된 수학 요소에 적용되는 MathAccent를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |
| accentCharacter | char | 악센트 문자 |

**반환값:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새로운 MathAccent