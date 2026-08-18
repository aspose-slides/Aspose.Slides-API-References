---
title: MathArray
second_title: Aspose.Slides for Java API Referencia
description: Függőleges tömböt ad meg egyenletekkel vagy bármilyen matematikai objektummal
type: docs
url: /hu/com.aspose.slides/matharray/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Megad egy függőleges tömböt egyenletekkel vagy bármilyen matematikai objektummal

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai tömböt, és a megadott elemet belehelyezi |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Létrehoz egy matematikai tömböt, és a megadott elemeket belehelyezi |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getArguments()](#getArguments--) | A tömb elemeinek halmaza |
| [getBaseJustification()](#getBaseJustification--) | Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum elosztás. Ha igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez lesz elosztva. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum elosztás. Ha igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez lesz elosztva. |
| [getObjectDistribution()](#getObjectDistribution--) | Objektum elosztás. Ha igaz, a tömb tartalma a tömb objektum maximális szélességéhez lesz elosztva. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Objektum elosztás. Ha igaz, a tömb tartalma a tömb objektum maximális szélességéhez lesz elosztva. |
| [getRowSpacingRule()](#getRowSpacingRule--) | A tömb elemei közötti függőleges távolság típusa. Alapértelmezett: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | A tömb elemei közötti függőleges távolság típusa. Alapértelmezett: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | A tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha Multiple, akkor fél sor. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | A tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha Multiple, akkor fél sor. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


Létrehoz egy matematikai tömböt, és a megadott elemet belehelyezi

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | A tömbbe helyezendő elem |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


Létrehoz egy matematikai tömböt, és a megadott elemeket belehelyezi

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | A tömbbe helyezendő elemek |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final int getBaseJustification()
```


Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center

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
public final void setBaseJustification(int value)
```


Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center

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
public final boolean getMaximumDistribution()
```


Maximum elosztás. Ha igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez lesz elosztva.

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
public final void setMaximumDistribution(boolean value)
```


Maximum elosztás. Ha igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez lesz elosztva.

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
public final boolean getObjectDistribution()
```


Objektum elosztás. Ha igaz, a tömb tartalma a tömb objektum maximális szélességéhez lesz elosztva.

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
public final void setObjectDistribution(boolean value)
```


Objektum elosztás. Ha igaz, a tömb tartalma a tömb objektum maximális szélességéhez lesz elosztva.

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
public final int getRowSpacingRule()
```


A tömb elemei közötti függőleges távolság típusa. Alapértelmezett: SingleLineGap

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
public final void setRowSpacingRule(int value)
```


A tömb elemei közötti függőleges távolság típusa. Alapértelmezett: SingleLineGap

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
public final long getRowSpacing()
```


A tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha Multiple, akkor fél sor. Alapértelmezett: 0

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
public final void setRowSpacing(long value)
```


A tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule értéke 3. Ebben az esetben a mértékegység pont, vagy ha Multiple, akkor fél sor. Alapértelmezett: 0

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]