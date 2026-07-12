---
title: IMathArray
second_title: Aspose.Slides Android-hoz Java API hivatkozás
description: Függőleges tömböt ad meg egyenletekkel vagy bármely matematikai objektummal
type: docs
url: /hu/com.aspose.slides/imatharray/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Függőleges tömböt ad meg egyenletekkel vagy bármely matematikai objektummal

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
| [getBaseJustification()](#getBaseJustification--) | Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg alulra, felülre vagy középre igazítható a tömbobjektumhoz képest. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg alulra, felülre vagy középre igazítható a tömbobjektumhoz képest. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution Amikor igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution Amikor igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik. |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution Amikor igaz, a tömb tartalma a tömbobjektum maximális szélességéhez igazodik. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution Amikor igaz, a tömb tartalma a tömbobjektum maximális szélességéhez igazodik. |
| [getRowSpacingRule()](#getRowSpacingRule--) | A tömbelemek közötti függőleges távolság típusa |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | A tömbelemek közötti függőleges távolság típusa |
| [getRowSpacing()](#getRowSpacing--) | Sorok közötti távolság egy tömbben. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy több esetben fél sor. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Sorok közötti távolság egy tömbben. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy több esetben fél sor. |
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

**Visszatér:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```


Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg alulra, felülre vagy középre igazítható a tömbobjektumhoz képest. Alapértelmezett érték: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Visszatér:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```


Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg alulra, felülre vagy középre igazítható a tömbobjektumhoz képest. Alapértelmezett érték: Center

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


Maximum Distribution Amikor igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Visszatér:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```


Maximum Distribution Amikor igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik.

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


Object Distribution Amikor igaz, a tömb tartalma a tömbobjektum maximális szélességéhez igazodik.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Visszatér:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```


Object Distribution Amikor igaz, a tömb tartalma a tömbobjektum maximális szélességéhez igazodik.

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


A tömbelemek közötti függőleges távolság típusa

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Visszatér:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```


A tömbelemek közötti függőleges távolság típusa

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


Sorok közötti távolság egy tömbben. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy több esetben fél sor. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Visszatér:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```


Sorok közötti távolság egy tömbben. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy több esetben fél sor. Alapértelmezett: 0

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