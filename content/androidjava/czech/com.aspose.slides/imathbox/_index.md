---
title: IMathBox
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Specifikuje logické zabalení (balení) matematického prvku.
type: docs
url: /cs/com.aspose.slides/imathbox/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specifikuje logické zabalení (balení) matematického prvku. Například objekt v rámečku může sloužit jako emulátor operátoru s nebo bez bodu zarovnání, jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalamování řádků uvnitř. Například operátor „==“ by měl být zabalen, aby se zabránilo zalomení řádku.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
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


Operátorový emulátor. Když je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Operátoroví emulátory se často používají, když se jeden nebo více znaků kombinuje do operátoru, například '=='. Výchozí hodnota: false

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


Operátorový emulátor. Když je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Operátoroví emulátory se často používají, když se jeden nebo více znaků kombinuje do operátoru, například '=='. Výchozí hodnota: false

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


Žádné zalomení. Tato vlastnost určuje vlastnost „unbreakable“ na objektovém rámečku. Když je true, v rámci rámečku nemohou nastat žádná zalomení řádku. To může být důležité pro operátorové emulátory, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou se v rámečku vyskytovat zalomení. Výchozí hodnota: true

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


Žádné zalomení. Tato vlastnost určuje vlastnost „unbreakable“ na objektovém rámečku. Když je true, v rámci rámečku nemohou nastat žádná zalomení řádku. To může být důležité pro operátorové emulátory, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou se v rámečku vyskytovat zalomení. Výchozí hodnota: true

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


Differenciál. Když je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává vhodné vodorovné mezery pro matematický diferenciál. Výchozí hodnota: false

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


Differenciál. Když je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává vhodné vodorovné mezery pro matematický diferenciál. Výchozí hodnota: false

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


Když je true, tento operátorový emulátor slouží jako bod zarovnání; to znamená, že určené body zarovnání v jiných rovnicích mohou být s ním zarovnány. Výchozí hodnota: false

--------------------

> ```
> Example:
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


Když je true, tento operátorový emulátor slouží jako bod zarovnání; to znamená, že určené body zarovnání v jiných rovnicích mohou být s ním zarovnány. Výchozí hodnota: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```


Explicitní zalomení určuje, zda existuje zalomení řádku na začátku objektu Box, aby se řádek zalamoval na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které bude použito jako bod zarovnání pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí hodnota: 0 (žádné explicitní zalomení)

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


Explicitní zalomení určuje, zda existuje zalomení řádku na začátku objektu Box, aby se řádek zalamoval na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které bude použito jako bod zarovnání pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí hodnota: 0 (žádné explicitní zalomení)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |