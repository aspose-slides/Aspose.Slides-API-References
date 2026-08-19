---
title: MathArray
second_title: Aspose.Slides för Java API-referens
description: Specificerar en vertikal matris av ekvationer eller andra matematiska objekt
type: docs
url: /sv/com.aspose.slides/matharray/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Specificerar en vertikal matris av ekvationer eller andra matematiska objekt

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Skapar en matematisk matris och placerar det angivna elementet i den |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Skapar en matematisk matris och placerar angivna element i den |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArguments()](#getArguments--) | Mängden objekt i matrisen |
| [getBaseJustification()](#getBaseJustification--) | Specificerar justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller centrum av ett matrisobjekt. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificerar justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller centrum av ett matrisobjekt. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximal fördelning När sann är matrisen justerad till maximal bredd av det innehållande elementet (sida, kolumn, cell etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximal fördelning När sann är matrisen justerad till maximal bredd av det innehållande elementet (sida, kolumn, cell etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Objektfördelning När sann är innehållet i matrisen justerat till matrisobjektets maximala bredd. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Objektfördelning När sann är innehållet i matrisen justerat till matrisobjektets maximala bredd. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Typen av vertikal avstånd mellan matriselement Standard: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Typen av vertikal avstånd mellan matriselement Standard: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Exakt i vilket fall måttenheten är punkter eller Multipel där måttenheten är halva rader. Standard: 0 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Exakt i vilket fall måttenheten är punkter eller Multipel där måttenheten är halva rader. Standard: 0 |
| [getChildren()](#getChildren--) | Hämta underordnade element |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


Skapar en matematisk matris och placerar det angivna elementet i den

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elementet att placera i matrisen |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


Skapar en matematisk matris och placerar angivna element i den

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Element att placera i matrisen |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Mängden objekt i matrisen

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
public final int getBaseJustification()
```


Specificerar justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller centrum av ett matrisobjekt. Standardvärde: Center

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
public final void setBaseJustification(int value)
```


Specificerar justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller centrum av ett matrisobjekt. Standardvärde: Center

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
public final boolean getMaximumDistribution()
```


Maximal fördelning När sann är matrisen justerad till maximal bredd av det innehållande elementet (sida, kolumn, cell etc.).

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
public final void setMaximumDistribution(boolean value)
```


Maximal fördelning När sann är matrisen justerad till maximal bredd av det innehållande elementet (sida, kolumn, cell etc.).

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
public final boolean getObjectDistribution()
```


Objektfördelning När sann är innehållet i matrisen justerat till matrisobjektets maximala bredd.

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
public final void setObjectDistribution(boolean value)
```


Objektfördelning När sann är innehållet i matrisen justerat till matrisobjektets maximala bredd.

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
public final int getRowSpacingRule()
```


Typen av vertikal avstånd mellan matriselement Standard: SingleLineGap

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
public final void setRowSpacingRule(int value)
```


Typen av vertikal avstånd mellan matriselement Standard: SingleLineGap

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
public final long getRowSpacing()
```


Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Exakt i vilket fall måttenheten är punkter eller Multipel där måttenheten är halva rader. Standard: 0

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
public final void setRowSpacing(long value)
```


Avstånd mellan rader i en matris. Används endast när RowSpacingRule är satt till 3. Exakt i vilket fall måttenheten är punkter eller Multipel där måttenheten är halva rader. Standard: 0

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]