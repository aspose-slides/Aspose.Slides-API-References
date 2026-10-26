---
title: MathAccent
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 기본과 결합 발음 구분 기호로 구성된 악센트 기능을 지정합니다. 예: ud835udc4eu0301
type: docs
url: /ko/com.aspose.slides/mathaccent/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

기본과 결합 발음 구분 기호로 구성된 악센트 기능을 지정합니다. 예: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | 기본 악센트 문자 값을 사용하여 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다 |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 악센트가 적용된 인수 |
| [getCharacter()](#getCharacter--) | 악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 결합 서캐플스 악센트 (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | 악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 결합 서캐플스 악센트 (U+0302) |
| [getChildren()](#getChildren--) | 하위 요소를 가져옵니다 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

기본 악센트 문자 값을 사용하여 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

지정된 수학 요소에 적용되는 수학 악센트를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 악센트를 적용할 수학 요소 |
| accentCharacter | char | 악센트 문자 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

악센트가 적용된 인수

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 결합 서캐플스 악센트 (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**반환값:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 결합 서캐플스 악센트 (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

하위 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps