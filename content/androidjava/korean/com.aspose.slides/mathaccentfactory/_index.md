---
title: MathAccentFactory
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 악센트를 만들 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathaccentfactory/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

수학 악센트를 만들 수 있도록 허용합니다

--------------------

COM 호환성을 위해
## 생성자

| Constructor | Description |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## 메서드

| Method | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 지정된 수학 요소에 기본 악센트 문자 값을 적용하여 수학 악센트를 생성합니다 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다 |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

지정된 수학 요소에 기본 악센트 문자 값을 적용하여 수학 악센트를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |
**반환:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - 새 수학 악센트
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

지정된 수학 요소에 적용되는 수학 악센트를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |
| accentCharacter | char | 악센트 문자 |
**반환:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - 새 수학 악센트