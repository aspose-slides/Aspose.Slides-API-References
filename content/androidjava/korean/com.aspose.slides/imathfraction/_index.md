---
title: IMathFraction
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 분자와 분모가 분수 기호로 구분된 분수 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathfraction/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

분자와 분모가 분수 기호로 구분된 분수 객체를 지정합니다. 분수 기호는 분수 속성에 따라 수평 또는 대각선이 될 수 있습니다. 분수 객체는 또한 분수 기호 없이 하나의 요소를 다른 요소 위에 배치하는 스택 함수도 나타내는 데 사용됩니다.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFractionType()](#getFractionType--) | 분수 유형 기본값: Bar |
| [setFractionType(int value)](#setFractionType-int-) | 분수 유형 기본값: Bar |
| [getNumerator()](#getNumerator--) | 분자 |
| [getDenominator()](#getDenominator--) | 분모 |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

분수 유형 기본값: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**반환:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```

분수 유형 기본값: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```

분자

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**반환:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```

분모

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**반환:**
[IMathElement](../../com.aspose.slides/imathelement)