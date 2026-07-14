---
title: MathFunction
second_title: Java API 레퍼런스를 이용한 Android용 Aspose.Slides
description: 인수의 함수를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathfunction/
---
**상속:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

인수의 함수를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathFunction 클래스의 새 인스턴스를 초기화합니다. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | MathFunction 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | 함수 이름 예를 들어, 함수 이름은 sin과 cos입니다 |
| [getBase()](#getBase--) | 함수 인수 |
| [getChildren()](#getChildren--) | 자식 요소 가져오기 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


MathFunction 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


MathFunction 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


함수 이름 예를 들어, 함수 이름은 sin과 cos입니다

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


함수 인수

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


자식 요소 가져오기

**반환값:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps