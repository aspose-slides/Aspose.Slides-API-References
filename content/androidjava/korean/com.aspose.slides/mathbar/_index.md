---
title: MathBar
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 기본 인수와 위바 또는 아래바로 구성된 바 함수를 지정합니다
type: docs
url: /ko/com.aspose.slides/mathbar/
---
**상속:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**모든 구현된 인터페이스:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

바 함수를 지정합니다. 기본 인수와 위바 또는 아래바로 구성됩니다.

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | 오버바(상단 위치)로 MathBar를 초기화합니다 |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | 지정된 위치로 MathBar를 초기화합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getPosition()](#getPosition--) | 바 라인의 위치. |
| [setPosition(int value)](#setPosition-int-) | 바 라인의 위치. |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


오버바(상단 위치)로 MathBar를 초기화합니다

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바가 적용되는 기본 요소 |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


지정된 위치로 MathBar를 초기화합니다

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바가 적용되는 기본 요소 |
| position | int | 바 라인의 위치. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


기본 인수

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


바 라인의 위치. 기본값: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**반환값:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


바 라인의 위치. 기본값: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


자식 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps