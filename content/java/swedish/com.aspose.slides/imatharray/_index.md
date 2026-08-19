---
title: IMathArray
second_title: Aspose.Slides för Java API-referens
description: Anger en vertikal matris av ekvationer eller andra matematiska objekt
type: docs
url: /sv/com.aspose.slides/imatharray/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Anger en vertikal matris av ekvationer eller andra matematiska objekt

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArguments()](#getArguments--) | Mängden av element i matrisen |
| [getBaseJustification()](#getBaseJustification--) | Anger inriktningsinställning för matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med bottom, top, eller center av ett matrisobjekt. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Anger inriktningsinställning för matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med bottom, top, eller center av ett matrisobjekt. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution När true, placeras matrisen med maximalt avstånd till den omgivande elementets bredd (page, column, cell, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution När true, placeras matrisen med maximalt avstånd till den omgivande elementets bredd (page, column, cell, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution När true, placeras innehållet i matrisen med maximalt avstånd till matrisobjektets bredd. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution När true, placeras innehållet i matrisen med maximalt avstånd till matrisobjektets bredd. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typen av vertikal avstånd mellan matrisens element |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typen av vertikal avstånd mellan matrisens element |
| [getRowSpacing()](#getRowSpacing--) | Avstånd mellan rader i en matris. Det används bara när RowSpacingRule är satt till 3. Exakt i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvlånga. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Avstånd mellan rader i en matris. Det används bara när RowSpacingRule är satt till 3. Exakt i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvlånga. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Mängden av element i matrisen

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

Anger inriktningsinställning för matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med bottom, top, eller center av ett matrisobjekt. Standardvärde: Center

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

Anger inriktningsinställning för matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med bottom, top, eller center av ett matrisobjekt. Standardvärde: Center

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

Maximum Distribution När true, placeras matrisen med maximalt avstånd till den omgivande elementets bredd (page, column, cell, etc.).

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

Maximum Distribution När true, placeras matrisen med maximalt avstånd till den omgivande elementets bredd (page, column, cell, etc.).

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

Object Distribution När true, placeras innehållet i matrisen med maximalt avstånd till matrisobjektets bredd.

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

Object Distribution När true, placeras innehållet i matrisen med maximalt avstånd till matrisobjektets bredd.

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

Avstånd mellan rader i en matris. Det används bara när RowSpacingRule är satt till 3. Exakt i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvlånga. Standard: 0

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

Avstånd mellan rader i en matris. Det används bara när RowSpacingRule är satt till 3. Exakt i det fallet är måttenheten punkter eller Multiple i det fallet är måttenheten halvlånga. Standard: 0

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