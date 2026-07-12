---
title: MathBox
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Meghatározza a matematikai elem logikai dobozolási csomagolását.
type: docs
url: /hu/com.aspose.slides/mathbox/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Meghatározza a matematikai elem logikai dobozolt (csomagolás) módját. Például egy dobozolt objektum szolgálhat operátor emulátorként kiindulási ponttal vagy anélkül, szolgálhat sorvágási pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket benne. Például a „==” operátort dobozni kell, hogy megakadályozzuk a sortöréseket.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Inicializálja a MathBox-ot a megadott elemmel argumentumként |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operátor emulátor. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operátor emulátor. |
| [getNoBreak()](#getNoBreak--) | Nemtörés Ez a tulajdonság meghatározza a dobozon a „törhetetlen” állapotot. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Nemtörés Ez a tulajdonság meghatározza a dobozon a „törhetetlen” állapotot. |
| [getDifferential()](#getDifferential--) | Differenciál Ha igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differenciál Ha igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Ha igaz, ez az operátor emulátor kiindulási pontként szolgál; azaz más egyenletek kijelölt kiindulási pontjai ehez igazíthatók. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Ha igaz, ez az operátor emulátor kiindulási pontként szolgál; azaz más egyenletek kijelölt kiindulási pontjai ehez igazíthatók. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz elején törik. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit törés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz elején törik. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlőkarakter tulajdonságok |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Inicializálja a MathBox-ot a megadott elemmel argumentumként

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az alap elem, amelyhez a doboz alkalmazva van. Lehet null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Operátor emulátor. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter szolgálhat sortörési pontként, és más operátorokhoz igazítható. Az operátor emulátorokat gyakran használják, ha egy vagy több glif egy operátort alkot, mint például a '=='. Alapértelmezett érték: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Visszatérési érték:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Operátor emulátor. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter szolgálhat sortörési pontként, és más operátorokhoz igazítható. Az operátor emulátorokat gyakran használják, ha egy vagy több glif egy operátort alkot, mint például a '=='. Alapértelmezett érték: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


Nemtörés Ez a tulajdonság meghatározza a dobozon a „törhetetlen” állapotot. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet több bináris operátorból álló operátor emulátorok esetén. Ha ez az elem nincs megadva, a dobozon belül megtörténhetnek törések. Alapértelmezett: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Visszatérési érték:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


Nemtörés Ez a tulajdonság meghatározza a dobozon a „törhetetlen” állapotot. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet több bináris operátorból álló operátor emulátorok esetén. Ha ez az elem nincs megadva, a dobozon belül megtörténhetnek törések. Alapértelmezett: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Differenciál Ha igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Visszatérési érték:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```


Differenciál Ha igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false

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
public final boolean getAlignmentPoint()
```


Ha igaz, ez az operátor emulátor kiindulási pontként szolgál; azaz más egyenletek kijelölt kiindulási pontjai ehez igazíthatók. Alapértelmezett: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Visszatérési érték:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Ha igaz, ez az operátor emulátor kiindulási pontként szolgál; azaz más egyenletek kijelölt kiindulási pontjai ehez igazíthatók. Alapértelmezett: false

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
public final byte getExplicitBreak()
```


Explicit break meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz elején törik. Meghatározza az előző sor matematikai szövegén lévő operátor sorszámát, amely az aktuális sor matematikai szövegének igazítási pontjaként szolgál; lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit törés)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Visszatérési érték:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```


Explicit break meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz elején törik. Meghatározza az előző sor matematikai szövegén lévő operátor sorszámát, amely az aktuális sor matematikai szövegének igazítási pontjaként szolgál; lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit törés)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vezérlőkarakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps