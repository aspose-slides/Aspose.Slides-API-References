---
title: IMathBox
second_title: Aspose.Slides Java API hivatkozás
description: Meghatározza a matematikai elem logikai dobozolását (csomagolását).
type: docs
url: /hu/com.aspose.slides/imathbox/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Meghatározza a matematikai elem logikai dobozolását (csomagolását). Például egy dobozolt objektum szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, sorbontási pontként, vagy csoportosítható úgy, hogy ne engedjen sortörést a belsejében. Például az "==" operátort dobozni kell a sortörések megelőzése érdekében.

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
| [getAlignmentPoint()](#getAlignmentPoint--) | Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben megadott igazítási pontok ehhez igazíthatók. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben megadott igazítási pontok ehhez igazíthatók. |
| [getExplicitBreak()](#getExplicitBreak--) | Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején lesz törve. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején lesz törve. |
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

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operátor emulátor. Amikor igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, hogy a karakter szolgálhat sorbontási pontként és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, ha egy vagy több glif kombinálódik operátorrá, például a '==' esetén. Alapértelmezett érték: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Visszatérési érték:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operátor emulátor. Amikor igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, hogy a karakter szolgálhat sorbontási pontként és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, ha egy vagy több glif kombinálódik operátorrá, például a '==' esetén. Alapértelmezett érték: false

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

Nincs törés. Ez a tulajdonság meghatározza a "unbreakable" (törhetetlen) tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet több bináris operátort tartalmazó operátor emulátorok esetén. Ha ez az elem nincs megadva, sortörés lehetséges a dobozon belül. Alapértelmezett: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Visszatérési érték:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Nincs törés. Ez a tulajdonság meghatározza a "unbreakable" (törhetetlen) tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet több bináris operátort tartalmazó operátor emulátorok esetén. Ha ez az elem nincs megadva, sortörés lehetséges a dobozon belül. Alapértelmezett: true

--------------------

> ```
> Példa:
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

Differenciál. Amikor igaz, a doboz differenciálként működik (például \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false

--------------------

> ```
> Példa:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
```

**Visszatérési érték:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differenciál. Amikor igaz, a doboz differenciálként működik (például \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false

--------------------

> ```
> Példa:
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

Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben megadott igazítási pontok ehhez igazíthatók. Alapértelmezett: false

--------------------

> ```
> Példa:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Visszatérési érték:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben megadott igazítási pontok ehhez igazíthatók. Alapértelmezett: false

--------------------

> ```
> Példa:
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

Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején lesz törve. Megadja az előző sorban lévő operátor számát a matematikai szövegben, amely a jelenlegi sor matematikai szövegének igazítási pontjaként lesz használva. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit törés)

--------------------

> ```
> Példa:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Visszatérési érték:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Az explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején lesz törve. Megadja az előző sorban lévő operátor számát a matematikai szövegben, amely a jelenlegi sor matematikai szövegének igazítási pontjaként lesz használva. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit törés)

--------------------

> ```
> Példa:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |