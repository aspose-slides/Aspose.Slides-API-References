---
title: IMathArray
second_title: Aspose.Slides för Android via Java API-referens
description: Anger en vertikal matris med ekvationer eller andra matematiska objekt
type: docs
url: /sv/com.aspose.slides/imatharray/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Anger en vertikal matris med ekvationer eller andra matematiska objekt

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArguments()](#getArguments--) | Mängden av objekt i matrisen |
| [getBaseJustification()](#getBaseJustification--) | Anger justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Anger justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution När true, matrisen placeras med maximal bredd av det innehållande elementet (sida, kolumn, cell osv.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution När true, matrisen placeras med maximal bredd av det innehållande elementet (sida, kolumn, cell osv.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution När true, innehållet i matrisen placeras med maximal bredd av matrisobjektet. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution När true, innehållet i matrisen placeras med maximal bredd av matrisobjektet. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typen av vertikal avstånd mellan matrisens element |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typen av vertikal avstånd mellan matrisens element |
| [getRowSpacing()](#getRowSpacing--) | Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Precis i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvrader. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Precis i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvrader. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Mängden av objekt i matrisen

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Returnerar:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Anger justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. Standardvärde: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Returnerar:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Anger justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. Standardvärde: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Maximum Distribution När true, matrisen placeras med maximal bredd av det innehållande elementet (sida, kolumn, cell osv.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Returnerar:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maximum Distribution När true, matrisen placeras med maximal bredd av det innehållande elementet (sida, kolumn, cell osv.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Object Distribution När true, innehållet i matrisen placeras med maximal bredd av matrisobjektet.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Returnerar:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Object Distribution När true, innehållet i matrisen placeras med maximal bredd av matrisobjektet.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

Typen av vertikal avstånd mellan matrisens element

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Returnerar:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

Typen av vertikal avstånd mellan matrisens element

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Precis i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvrader. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Returnerar:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Precis i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvrader. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |