---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math accent
type: docs
url: /ko/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

수학 억양을 만들 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 지정된 수학 요소에 기본 억양 문자 값을 적용하여 수학 억양을 생성합니다 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 지정된 수학 요소에 억양을 적용하여 수학 억양을 생성합니다 |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


지정된 수학 요소에 기본 억양 문자 값을 적용하여 수학 억양을 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 억양을 적용할 수학 요소 |

**반환값:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새 수학 억양
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


지정된 수학 요소에 억양을 적용하여 수학 억양을 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 억양을 적용할 수학 요소 |
| accentCharacter | char | 억양 문자 |

**반환값:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새 수학 억양