---
title: MathFraction
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 분수선으로 구분된 분자와 분모로 구성된 분수 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathfraction/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

분자와 분모가 분수선으로 구분된 분수 객체를 지정합니다. 분수선은 분수 속성에 따라 가로 또는 대각선이 될 수 있습니다. 또한 분수 객체는 분수선 없이 하나의 요소를 다른 요소 위에 배치하는 스택 함수도 나타내는 데 사용됩니다.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 지정된 분자, 분모 및 유형으로 MathFraction을 초기화합니다 |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 지정된 분자와 분모로 'Bar' 유형의 MathFraction을 초기화합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fraction type 기본값: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction type 기본값: Bar |
| [getNumerator()](#getNumerator--) | 분자 |
| [getDenominator()](#getDenominator--) | 분모 |
| [getChildren()](#getChildren--) | 자식 요소 가져오기 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

지정된 분자, 분모 및 유형으로 MathFraction을 초기화합니다

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 분자 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |
| fractionType | int | 분수 유형 |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

지정된 분자와 분모로 'Bar' 유형의 MathFraction을 초기화합니다

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 분자 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```

Fraction type 기본값: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**반환값:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```

Fraction type 기본값: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```

분자

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```

분모

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소 가져오기

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps