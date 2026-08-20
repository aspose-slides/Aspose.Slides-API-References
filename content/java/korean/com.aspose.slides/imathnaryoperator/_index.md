---
title: IMathNaryOperator
second_title: Aspose.Slides Java API 레퍼런스
description: Summation 및 Integral과 같은 N-ary 수학 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathnaryoperator/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

N-ary 수학 객체(예: Summation 및 Integral)를 지정합니다. 연산자와 베이스(또는 피연산자), 선택적인 상한 및 하한으로 구성됩니다. N-ary 연산자의 예로는 Summation, Union, Intersection, Integral이 있습니다.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 베이스 인수 |
| [getSubscript()](#getSubscript--) | 예를 들어 적분의 경우 하한을 설정하는 첨자 인수를 지정합니다 |
| [getSuperscript()](#getSuperscript--) | 예를 들어 적분의 경우 상한을 설정하는 위첨자 인수를 지정합니다 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


베이스 인수

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


예를 들어 적분의 경우 하한을 설정하는 첨자 인수를 지정합니다

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```


**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


예를 들어 적분의 경우 상한을 설정하는 위첨자 인수를 지정합니다

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)