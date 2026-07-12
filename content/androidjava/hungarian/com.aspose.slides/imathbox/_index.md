---
title: IMathBox
second_title: Aspose.Slides for Android a Java API referencia szerint
description: Meghatározza a matematikai elem logikai csomagolását.
type: docs
url: /hu/com.aspose.slides/imathbox/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Meghatározza a matematikai elem logikai csomagolását (dobozolását). Például egy dobozolt objektum szolgálhat operátor emulátorként egyigazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket a belsejében. Például a "==" operátort dobozni kell a sortörések megelőzéséhez.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operátor emulátor. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operátor emulátor. |
| [getNoBreak()](#getNoBreak--) | Nincs törés. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Nincs törés. |
| [getDifferential()](#getDifferential--) | Differenciál. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differenciál. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Ha igaz, ez az operátor emulátor igazítási pontként szolgál; azaz a többi egyenletben kijelölt igazítási pontok ehhez igazíthatók. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Ha igaz, ez az operátor emulátor igazítási pontként szolgál; azaz a többi egyenletben kijelölt igazítási pontok ehhez igazíthatók. |
| [getExplicitBreak()](#getExplicitBreak--) | Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, úgy hogy a sor a box objektum elején törik. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, úgy hogy a sor a box objektum elején törik. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Alap argumentum

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operátor emulátor. Ha igaz, a box és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, hogy például a karakter szolgálhat sortörés pontként, és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, ha egy vagy több glif kombinálódik egy operátorrá, például a '=='. Alapértelmezett érték: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Visszatér:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operátor emulátor. Ha igaz, a box és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, hogy például a karakter szolgálhat sortörés pontként, és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, ha egy vagy több glif kombinálódik egy operátorrá, például a '=='. Alapértelmezett érték: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Nincs törés. Ez a tulajdonság meghatározza a "unbreakable" tulajdonságot az objektum boxon. Ha igaz, a boxon belül nem fordulhat elő sor törés. Ez fontos lehet olyan operátor emulátoroknál, amelyek több bináris operátorból állnak. Ha ez az elem nincs megadva, a boxon belül előfordulhatnak törések. Alapértelmezett: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```


**Visszatér:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Nincs törés. Ez a tulajdonság meghatározza a "unbreakable" tulajdonságot az objektum boxon. Ha igaz, a boxon belül nem fordulhat elő sor törés. Ez fontos lehet olyan operátor emulátoroknál, amelyek több bináris operátorból állnak. Ha ez az elem nincs megadva, a boxon belül előfordulhatnak törések. Alapértelmezett: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differenciál. Ha igaz, a box differenciálként működik (például \ud835\udc51\ud835\udc65 egy integrandban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Visszatér:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differenciál. Ha igaz, a box differenciálként működik (például \ud835\udc51\ud835\udc65 egy integrandban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Ha igaz, ez az operátor emulátor igazítási pontként szolgál; azaz a többi egyenletben kijelölt igazítási pontok ehhez igazíthatók. Alapértelmezett: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Visszatér:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Ha igaz, ez az operátor emulátor igazítási pontként szolgál; azaz a többi egyenletben kijelölt igazítási pontok ehhez igazíthatók. Alapértelmezett: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, úgy hogy a sor a box objektum elején törik. Meghatározza a matematikai szöveg előző sorában lévő operátor számát, amely az aktuális sor igazítási pontjaként szolgál; lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit törés)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Visszatér:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, úgy hogy a sor a box objektum elején törik. Meghatározza a matematikai szöveg előző sorában lévő operátor számát, amely az aktuális sor igazítási pontjaként szolgál; lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit törés)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |