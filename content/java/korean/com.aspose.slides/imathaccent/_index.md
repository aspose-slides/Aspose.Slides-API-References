---
title: IMathAccent
second_title: Aspose.Slides for Java API 참조
description: 베이스와 결합 부호를 포함하는 악센트 기능을 지정합니다. 예: ud835udc4eu0301
type: docs
url: /ko/com.aspose.slides/imathaccent/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

베이스와 결합 부호를 포함하는 악센트 기능을 지정합니다. 예: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 악센트가 적용된 인수 |
| [getCharacter()](#getCharacter--) | 악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위에 있어야 합니다 기본값: 결합 서키프 악센트 (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | 악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위에 있어야 합니다 기본값: 결합 서키프 악센트 (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```

악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위에 있어야 합니다 기본값: 결합 서키프 악센트 (U+0302)

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
public abstract void setCharacter(char value)
```

악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위에 있어야 합니다 기본값: 결합 서키프 악센트 (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |