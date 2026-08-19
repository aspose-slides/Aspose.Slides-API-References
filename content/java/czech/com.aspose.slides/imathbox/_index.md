---
title: IMathBox
second_title: Aspose.Slides pro Java – reference API
description: Specifikuje logické balení (zabalení) matematického prvku.
type: docs
url: /cs/com.aspose.slides/imathbox/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specifikuje logické balení (zabalení) matematického prvku. Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. Například operátor "==" by měl být zabalen, aby se zabránilo zalomení řádku.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulátor operátoru. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulátor operátoru. |
| [getNoBreak()](#getNoBreak--) | Bez zalomení. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Bez zalomení. |
| [getDifferential()](#getDifferential--) | Differenciál. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differenciál. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Když je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Když je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalomí na začátku objektu box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalomí na začátku objektu box. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Základní argument

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Emulátor operátoru. Když je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Emulátory operátorů se často používají, když se jeden nebo více glyfů spojí do operátoru, například '=='. Výchozí hodnota: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Vrací:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Emulátor operátoru. Když je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Emulátory operátorů se často používají, když se jeden nebo více glyfů spojí do operátoru, například '=='. Výchozí hodnota: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Bez zalomení. Tato vlastnost specifikuje vlastnost „unbreakable“ objektu box. Když je true, v rámci boxu nemohou nastat žádná zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není zadán, mohou v boxu nastat zalomení. Výchozí: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Vrací:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Bez zalomení. Tato vlastnost specifikuje vlastnost „unbreakable“ objektu box. Když je true, v rámci boxu nemohou nastat žádná zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není zadán, mohou v boxu nastat zalomení. Výchozí: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differenciál. Když je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 ve integrandu) a získá odpovídající vodorovné mezery pro matematický diferenciál. Výchozí: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Vrací:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differenciál. Když je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 ve integrandu) a získá odpovídající vodorovné mezery pro matematický diferenciál. Výchozí: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Když je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí: false

--------------------

> ```
> Příklad:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Vrací:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Když je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí: false

--------------------

> ```
> Příklad:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalomí na začátku objektu box. Určuje číslo operátoru na předchozím řádku matematického textu, které bude použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Vrací:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalomí na začátku objektu box. Určuje číslo operátoru na předchozím řádku matematického textu, které bude použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení)

--------------------

> ```
> Příklad:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |