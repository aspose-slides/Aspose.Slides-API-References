---
title: IMathBar
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 기본 인수와 위바 또는 아래바로 구성된 바 함수를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathbar/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

바 함수를 지정합니다. 이 함수는 기본 인수와 위바 혹은 아래바로 구성됩니다.

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getPosition()](#getPosition--) | 바 라인의 위치. |
| [setPosition(int value)](#setPosition-int-) | 바 라인의 위치. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

기본 인수

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

바 라인의 위치. 기본값: 위

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**반환값:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

바 라인의 위치. 기본값: 위

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |