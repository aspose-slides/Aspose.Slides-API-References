---
title: IMathFraction
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: 分子と分母が分数バーで区切られた分数オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathfraction/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

分数オブジェクトを指定します。分子と分母が分数バーで区切られます。分数バーは、分数のプロパティに応じて横方向または斜め方向に設定できます。この分数オブジェクトは、スタック関数も表すために使用されます。スタック関数は、要素を別の要素の上に配置しますが、分数バーは使用しません。

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFractionType()](#getFractionType--) | 分数タイプ デフォルト: Bar |
| [setFractionType(int value)](#setFractionType-int-) | 分数タイプ デフォルト: Bar |
| [getNumerator()](#getNumerator--) | 分子 |
| [getDenominator()](#getDenominator--) | 分母 |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


分数タイプ デフォルト: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**戻り値:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


分数タイプ デフォルト: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


分子

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


分母

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)