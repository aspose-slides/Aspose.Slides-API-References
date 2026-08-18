---
title: IMathArray
second_title: Aspose.Slides a Java API referencia
description: Függőleges egyenletek vagy bármely matematikai objektumok tömbjét határozza meg
type: docs
url: /hu/com.aspose.slides/imatharray/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Függőleges egyenletek vagy bármely matematikai objektumok tömbjét határozza meg

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getArguments()](#getArguments--) | A tömb elemeinek halmaza |
| [getBaseJustification()](#getBaseJustification--) | Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg a tömb objektum aljához, tetejéhez vagy középéhez igazítható. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg a tömb objektum aljához, tetejéhez vagy középéhez igazítható. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximális eloszlás: Ha igaz, a tömb a környező elem (oldal, oszlop, cella stb.) legnagyobb szélességére lesz nyújtva. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximális eloszlás: Ha igaz, a tömb a környező elem (oldal, oszlop, cella stb.) legnagyobb szélességére lesz nyújtva. |
| [getObjectDistribution()](#getObjectDistribution--) | Objektum eloszlás: Ha igaz, a tömb tartalma a tömb objektum legnagyobb szélességére lesz nyújtva. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Objektum eloszlás: Ha igaz, a tömb tartalma a tömb objektum legnagyobb szélességére lesz nyújtva. |
| [getRowSpacingRule()](#getRowSpacingRule--) | A tömb elemei közötti függőleges távolság típusa |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | A tömb elemei közötti függőleges távolság típusa |
| [getRowSpacing()](#getRowSpacing--) | Távolság a tömb sorai között. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha több, akkor fél sor. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Távolság a tömb sorai között. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha több, akkor fél sor. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


A tömb elemeinek halmaza

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Visszatérési érték:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```


Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg a tömb objektum aljához, tetejéhez vagy középéhez igazítható. Alapértelmezett érték: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Visszatérési érték:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```


Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg a tömb objektum aljához, tetejéhez vagy középéhez igazítható. Alapértelmezett érték: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```


Maximális eloszlás: Ha igaz, a tömb a környező elem (oldal, oszlop, cella stb.) legnagyobb szélességére lesz nyújtva.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Visszatérési érték:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```


Maximális eloszlás: Ha igaz, a tömb a környező elem (oldal, oszlop, cella stb.) legnagyobb szélességére lesz nyújtva.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```


Objektum eloszlás: Ha igaz, a tömb tartalma a tömb objektum legnagyobb szélességére lesz nyújtva.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Visszatérési érték:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```


Objektum eloszlás: Ha igaz, a tömb tartalma a tömb objektum legnagyobb szélességére lesz nyújtva.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```


A tömb elemei közötti függőleges távolság típusa

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Visszatérési érték:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```


A tömb elemei közötti függőleges távolság típusa

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```


Távolság a tömb sorai között. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha több, akkor fél sor. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Visszatérési érték:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```


Távolság a tömb sorai között. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha több, akkor fél sor. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |