---
title: MathBox
second_title: Aspose.Slides för Java API-referens
description: Anger den logiska paketeringen av ett matematiskt element.
type: docs
url: /sv/com.aspose.slides/mathbox/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Anger den logiska kapslingen (paketeringen) av ett matematiskt element. Till exempel kan ett kapslat objekt fungera som en operatoremulatör med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inom den inte tillåts. Till exempel bör operatorn "==" kapslas för att förhindra radbrytningar.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Initierar MathBox med det angivna elementet som argument |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operatoremulatör. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operatoremulatör. |
| [getNoBreak()](#getNoBreak--) | Ingen brytning Denna egenskap specificerar egenskapen "unbreakable" på objektboxen. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Ingen brytning Denna egenskap specificerar egenskapen "unbreakable" på objektboxen. |
| [getDifferential()](#getDifferential--) | Differential När sann, fungerar boxen som en differential (t.ex. \\ud835\\udc51\\ud835\\udc65 i en integrand), och får lämplig horisontell avstånd för den matematiska differentialen. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential När sann, fungerar boxen som en differential (t.ex. \\ud835\\udc51\\ud835\\udc65 i en integrand), och får lämplig horisontell avstånd för den matematiska differentialen. |
| [getAlignmentPoint()](#getAlignmentPoint--) | När sann fungerar denna operatoremulatör som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | När sann fungerar denna operatoremulatör som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts vid objektets början. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts vid objektets början. |
| [getChildren()](#getChildren--) | Hämta underordnade element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrollteckenegenskaper |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Initierar MathBox med det angivna elementet som argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Basiselementet som boxen appliceras på. Kan vara null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Operatoremulatör. När sann beter sig boxen och dess innehåll som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för en radbrytning och kan justeras till andra operatorer. Operatoremulatörer används ofta när en eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Returnerar:** boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Operatoremulatör. När sann beter sig boxen och dess innehåll som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för en radbrytning och kan justeras till andra operatorer. Operatoremulatörer används ofta när en eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Ingen brytning Denna egenskap specificerar egenskapen "unbreakable" på objektboxen. När sann kan inga radbrytningar inträffa inom boxen. Detta kan vara viktigt för operatoremulatörer som består av mer än en binär operator. När detta element inte anges kan brytningar inträffa i boxen. Standard: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Returnerar:** boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Ingen brytning Denna egenskap specificerar egenskapen "unbreakable" på objektboxen. När sann kan inga radbrytningar inträffa inom boxen. Detta kan vara viktigt för operatoremulatörer som består av mer än en binär operator. När detta element inte anges kan brytningar inträffa i boxen. Standard: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Differential När sann, fungerar boxen som en differential (t.ex. \\ud835\\udc51\\ud835\\udc65 i en integrand), och får lämplig horisontell avstånd för den matematiska differentialen. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Returnerar:** boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

Differential När sann, fungerar boxen som en differential (t.ex. \\ud835\\udc51\\ud835\\udc65 i en integrand), och får lämplig horisontell avstånd för den matematiska differentialen. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

När sann fungerar denna operatoremulatör som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Returnerar:** boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

När sann fungerar denna operatoremulatör som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts vid objektets början. Anger numret på operatorn på föregående rad av matematisk text som ska användas som justeringspunkt för den aktuella raden av matematisk text. Möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Returnerar:** byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts vid objektets början. Anger numret på operatorn på föregående rad av matematisk text som ska användas som justeringspunkt för den aktuella raden av matematisk text. Möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrollteckenegenskaper

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps