---
title: IMathBox
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar den logiska inramningen och paketeringen av ett matematiskt element.
type: docs
url: /sv/com.aspose.slides/imathbox/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specificerar den logiska inramningen (paketeringen) av matematisk element. Till exempel kan ett inramat objekt fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inom det inte tillåts. Till exempel bör operatorn "==" inramas för att förhindra radbrytningar.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator-emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator-emulator. |
| [getNoBreak()](#getNoBreak--) | Ingen radbrytning. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Ingen radbrytning. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | När true, fungerar denna operator-emulator som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | När true, fungerar denna operator-emulator som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit brytning specificerar om det finns en radbrytning i början av Box-objektet, så att raden bryts vid start av Box-objektet. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit brytning specificerar om det finns en radbrytning i början av Box-objektet, så att raden bryts vid start av Box-objektet. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operator-emulator. När true, beter sig Box-objektet och dess innehåll som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för en radbrytning och kan justeras mot andra operatorer. Operator-emulatorer används ofta när ett eller flera tecken kombineras för att bilda en operator, såsom '=='. Standardvärde: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Returnerar:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operator-emulator. När true, beter sig Box-objektet och dess innehåll som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för en radbrytning och kan justeras mot andra operatorer. Operator-emulatorer används ofta när ett eller flera tecken kombineras för att bilda en operator, såsom '=='. Standardvärde: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Ingen radbrytning. Denna egenskap specificerar den "oavbrytbara" egenskapen på Box-objektet. När true, kan inga radbrytningar inträffa inom Box-objektet. Detta kan vara viktigt för operator-emulatorer som består av mer än en binär operator. När detta element inte är specificerat, kan brytningar inträffa i Box-objektet. Standard: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Returnerar:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Ingen radbrytning. Denna egenskap specificerar den "oavbrytbara" egenskapen på Box-objektet. När true, kan inga radbrytningar inträffa inom Box-objektet. Detta kan vara viktigt för operator-emulatorer som består av mer än en binär operator. När detta element inte är specificerat, kan brytningar inträffa i Box-objektet. Standard: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differential. När true, fungerar Box-objektet som ett differential (t.ex. \\ud835\\udc51\\ud835\\udc65 i en integrand), och får lämplig horisontell avstånd för det matematiska differentialet. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Returnerar:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differential. När true, fungerar Box-objektet som ett differential (t.ex. \\ud835\\udc51\\ud835\\udc65 i en integrand), och får lämplig horisontell avstånd för det matematiska differentialet. Standard: false

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
public abstract boolean getAlignmentPoint()
```

När true, fungerar denna operator-emulator som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Returnerar:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

När true, fungerar denna operator-emulator som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. Standard: false

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
public abstract byte getExplicitBreak()
```

Explicit brytning specificerar om det finns en radbrytning i början av Box-objektet, så att raden bryts vid start av Box-objektet. Anger numret på operatorn på föregående rad av matematisk text som ska användas som justeringspunkt för den aktuella raden av matematisk text. Möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Returnerar:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Explicit brytning specificerar om det finns en radbrytning i början av Box-objektet, så att raden bryts vid start av Box-objektet. Anger numret på operatorn på föregående rad av matematisk text som ska användas som justeringspunkt för den aktuella raden av matematisk text. Möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)

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