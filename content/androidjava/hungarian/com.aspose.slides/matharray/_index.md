---
title: MathArray
second_title: Aspose.Slides Androidra a Java API hivatkozásán keresztül
description: Függőleges tömböt ad meg egyenletekhez vagy bármely matematikai objektumhoz
type: docs
url: /hu/com.aspose.slides/matharray/
---
**Öröklés:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden implementált interfész:**  
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)  
```
public final class MathArray extends MathElementBase implements IMathArray
```

Függőleges tömböt ad meg egyenletekhez vagy bármely matematikai objektumhoz

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai tömböt, és a megadott elemet elhelyezi benne |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Létrehoz egy matematikai tömböt, és a megadott elemeket elhelyezi benne |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getArguments()](#getArguments--) | Az array elemeinek halmaza |
| [getBaseJustification()](#getBaseJustification--) | Meghatározza az array környező szöveghez viszonyló igazítását. Az arrayt körülvevő szöveg alulra, felülre vagy az array objektum közepére igazítható. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Meghatározza az array környező szöveghez viszonyló igazítását. Az arrayt körülvevő szöveg alulra, felülre vagy az array objektum közepére igazítható. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum elosztás: ha igaz, az array a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum elosztás: ha igaz, az array a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik. |
| [getObjectDistribution()](#getObjectDistribution--) | Objektum elosztás: ha igaz, az array tartalma a maximális szélességhez igazodik az array objektumban. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Objektum elosztás: ha igaz, az array tartalma a maximális szélességhez igazodik az array objektumban. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Az array elemei közti függőleges távolság típusa. Alapértelmezett: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Az array elemei közti függőleges távolság típusa. Alapértelmezett: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Az array sorai közti távolság. Csak akkor használható, ha a RowSpacingRule 3-ra van állítva. Ebben az esetben a mértékegység pont vagy többes, ha a mértékegység fél sor. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Az array sorai közti távolság. Csak akkor használható, ha a RowSpacingRule 3-ra van állítva. Ebben az esetben a mértékegység pont vagy többes, ha a mértékegység fél sor. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Létrehoz egy matematikai tömböt, és a megadott elemet elhelyezi benne

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | A tömbbe elhelyezendő elem |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Létrehoz egy matematikai tömböt, és a megadott elemeket elhelyezi benne

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | A tömbbe elhelyezendő elemek |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Az array elemeinek halmaza

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

Meghatározza az array környező szöveghez viszonyló igazítását. Az arrayt körülvevő szöveg alulra, felülre vagy az array objektum közepére igazítható. Alapértelmezett érték: Center

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

Meghatározza az array környező szöveghez viszonyló igazítását. Az arrayt körülvevő szöveg alulra, felülre vagy az array objektum közepére igazítható. Alapértelmezett érték: Center

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

Maximum elosztás: ha igaz, az array a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik.

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

Maximum elosztás: ha igaz, az array a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességéhez igazodik.

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

Objektum elosztás: ha igaz, az array tartalma a maximális szélességhez igazodik az array objektumban.

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

Objektum elosztás: ha igaz, az array tartalma a maximális szélességhez igazodik az array objektumban.

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

Az array elemei közti függőleges távolság típusa. Alapértelmezett: SingleLineGap

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

Az array elemei közti függőleges távolság típusa. Alapértelmezett: SingleLineGap

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

Az array sorai közti távolság. Csak akkor használható, ha a RowSpacingRule 3-ra van állítva. Ebben az esetben a mértékegység pont vagy többes, ha a mértékegység fél sor. Alapértelmezett: 0

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

Az array sorai közti távolság. Csak akkor használható, ha a RowSpacingRule 3-ra van állítva. Ebben az esetben a mértékegység pont vagy többes, ha a mértékegység fél sor. Alapértelmezett: 0

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