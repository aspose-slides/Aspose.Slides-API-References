---
title: MathBox
second_title: Aspose.Slides Java API Referencia
description: Meghatározza a matematikai elem logikai dobozolását (csomagolását).
type: docs
url: /hu/com.aspose.slides/mathbox/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Meghatározza a matematikai elem logikai dobozolását (csomagolását). Például egy dobozolt objektum szolgálhat operátor emulátorként igaz vagy hamis igazítási ponttal, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedjen sortöréseket belül. Például a "==" operátort dobozzal kell ellátni, hogy megakadályozzuk a sortöréseket.

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
| [getNoBreak()](#getNoBreak--) | Nincs törés Ez a tulajdonság határozza meg az "unbreakable" tulajdonságot az objektumdobozon. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Nincs törés Ez a tulajdonság határozza meg az "unbreakable" tulajdonságot az objektumdobozon. |
| [getDifferential()](#getDifferential--) | Differenciál Amikor igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megfelelő vízszintes térközt kap a matematikai differenciálhoz. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differenciál Amikor igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megfelelő vízszintes térközt kap a matematikai differenciálhoz. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben meghatározott igazítási pontok ehhez igazíthatók. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben meghatározott igazítási pontok ehhez igazíthatók. |
| [getExplicitBreak()](#getExplicitBreak--) | Az explicit sortörés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején törik. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Az explicit sortörés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején törik. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az alap elem, amelyre a doboz alkalmazva van. Lehet null. |

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

Operátor emulátor. Amikor igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter szolgálhat sortörés pontként, és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, ha egy vagy több glif kombinálódik egy operátor létrehozásához, például a '=='. Alapérték: false

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

Operátor emulátor. Amikor igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter szolgálhat sortörés pontként, és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, ha egy vagy több glif kombinálódik egy operátor létrehozásához, például a '=='. Alapérték: false

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

Nincs törés Ez a tulajdonság határozza meg az "unbreakable" tulajdonságot az objektumdobozon. Amikor igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet operátor emulátoroknál, amelyek több bináris operátorból állnak. Ha ez az elem nincs megadva, sortörések fordulhatnak elő a dobozon belül. Alapértelmezett: true

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

Nincs törés Ez a tulajdonság határozza meg az "unbreakable" tulajdonságot az objektumdobozon. Amikor igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet operátor emulátoroknál, amelyek több bináris operátorból állnak. Ha ez az elem nincs megadva, sortörések fordulhatnak elő a dobozon belül. Alapértelmezett: true

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

Differenciál Amikor igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megfelelő vízszintes térközt kap a matematikai differenciálhoz. Alapértelmezett: false

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

Differenciál Amikor igaz, a doboz differenciálként működik (pl. \\ud835\\udc51\\ud835\\udc65 egy integrandusban), és megfelelő vízszintes térközt kap a matematikai differenciálhoz. Alapértelmezett: false

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

Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben meghatározott igazítási pontok ehhez igazíthatók. Alapértelmezett: false

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

Amikor igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben meghatározott igazítási pontok ehhez igazíthatók. Alapértelmezett: false

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

Az explicit sortörés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején töri meg magát. Meghatározza az előző sor matematikai szövegében lévő operátor számát, amely az aktuális sor matematikai szövegének igazítási pontjaként szolgál; lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit sortörés)

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

Az explicit sortörés meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején töri meg magát. Meghatározza az előző sor matematikai szövegében lévő operátor számát, amely az aktuális sor matematikai szövegének igazítási pontjaként szolgál; lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit sortörés)

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

Vezérlő karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps