---
title: MathBox
second_title: Aspose.Slides pro Java API Reference
description: Určuje logické balení matematického prvku.
type: docs
url: /cs/com.aspose.slides/mathbox/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Určuje logické seskupení (balení) matematického prvku. Například objekt v krabici může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby v rámci něj nebylo povoleno zalamování řádků. Například operátor "==" by měl být zabalen, aby se zabránilo zalomení řádku.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Inicializuje MathBox s určeným elementem jako argument |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulátor operátoru. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulátor operátoru. |
| [getNoBreak()](#getNoBreak--) | No break Tato vlastnost specifikuje vlastnost "unbreakable" na objektové krabici. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break Tato vlastnost specifikuje vlastnost "unbreakable" na objektové krabici. |
| [getDifferential()](#getDifferential--) | Differential Když je true, krabice funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává vhodné vodorovné mezery pro matematický diferenciál. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential Když je true, krabice funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává vhodné vodorovné mezery pro matematický diferenciál. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj. určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj. určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicitní zalomení specifikuje, zda je na začátku objektu Box nový řádek, takže řádek se zalamuje na začátku objektu box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicitní zalomení specifikuje, zda je na začátku objektu Box nový řádek, takže řádek se zalamuje na začátku objektu box. |
| [getChildren()](#getChildren--) | Získá podřízené elementy |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídicích znaků |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Inicializuje MathBox s určeným elementem jako argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní element, na který se aplikuje box. Může být null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Základní argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```


**Návratová hodnota:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Emulátor operátoru. Když je true, krabice a její obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Emulátory operátorů se často používají, když se jeden nebo více glyfů spojí do operátoru, například '=='. Výchozí hodnota: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Návratová hodnota:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Emulátor operátoru. Když je true, krabice a její obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Emulátory operátorů se často používají, když se jeden nebo více glyfů spojí do operátoru, například '=='. Výchozí hodnota: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


No break Tato vlastnost specifikuje vlastnost "unbreakable" na objektové krabici. Když je true, uvnitř krabice nemohou nastat žádné zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když není tento prvek specifikován, mohou se v krabici vyskytnout zalomení. Výchozí hodnota: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Návratová hodnota:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


No break Tato vlastnost specifikuje vlastnost "unbreakable" na objektové krabici. Když je true, uvnitř krabice nemohou nastat žádné zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když není tento prvek specifikován, mohou se v krabici vyskytnout zalomení. Výchozí hodnota: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Differential Když je true, krabice funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává vhodné vodorovné mezery pro matematický diferenciál. Výchozí hodnota: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Návratová hodnota:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```


Differential Když je true, krabice funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává vhodné vodorovné mezery pro matematický diferenciál. Výchozí hodnota: false

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
public final boolean getAlignmentPoint()
```


Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj. určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí hodnota: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Návratová hodnota:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj. určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí hodnota: false

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
public final byte getExplicitBreak()
```


Explicitní zalomení specifikuje, zda je na začátku objektu Box nový řádek, takže řádek se zalamuje na začátku objektu box. Určuje číslo operátoru na předchozím řádku matematického textu, který bude použit jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí hodnota: 0 (žádné explicitní zalomení)

--------------------

> ```
> Příklad:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```


**Návratová hodnota:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```


Explicitní zalomení specifikuje, zda je na začátku objektu Box nový řádek, takže řádek se zalamuje na začátku objektu box. Určuje číslo operátoru na předchozím řádku matematického textu, který bude použit jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí hodnota: 0 (žádné explicitní zalomení)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřízené elementy

**Návratová hodnota:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídicích znaků

**Návratová hodnota:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps