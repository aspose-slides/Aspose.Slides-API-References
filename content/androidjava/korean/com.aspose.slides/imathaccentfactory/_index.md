---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 수학 악센트를 만들 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

수학 악센트를 만들 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

지정된 수학 요소에 기본 악센트 문자 값을 적용하여 수학 악센트를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |

**반환값:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새로운 수학 악센트
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

지정된 수학 요소에 악센트를 적용하여 수학 악센트를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |
| accentCharacter | char | 악센트 문자 |

**반환값:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새로운 수학 악센트