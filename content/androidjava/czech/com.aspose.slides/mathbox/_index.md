---
title: MathBox
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Specifikuje logické zabalení (balení) matematického prvku.
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

Specifikuje logické zabalení (balení) matematického prvku. Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby nepovoloval zalomení řádků uvnitř. Například operátor "==" by měl být zabalen, aby se zabránilo zalomení řádku.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Inicializuje MathBox s určeným prvkem jako argument |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulátor operátoru. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulátor operátoru. |
| [getNoBreak()](#getNoBreak--) | Bez zalomení Tato vlastnost určuje vlastnost "unbreakable" na objektovém boxu. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Bez zalomení Tato vlastnost určuje vlastnost "unbreakable" na objektovém boxu. |
| [getDifferential()](#getDifferential--) | Diferenciál. Pokud je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává odpovídající vodorovné odsazení pro matematický diferenciál. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferenciál. Pokud je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává odpovídající vodorovné odsazení pro matematický diferenciál. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Pokud je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Pokud je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalamuje na začátku objektu Box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalamuje na začátku objektu Box. |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídících znaků |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Inicializuje MathBox s určeným prvkem jako argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se box aplikuje. Může být null. |

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

Emulátor operátoru. Pokud je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Emulátory operátorů se často používají, když se jeden nebo více glifů spojuje do operátoru, například '=='. Výchozí hodnota: false

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

Emulátor operátoru. Pokud je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Emulátory operátorů se často používají, když se jeden nebo více glifů spojuje do operátoru, například '=='. Výchozí hodnota: false

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

Bez zalomení. Tato vlastnost určuje vlastnost "unbreakable" na objektovém boxu. Pokud je true, v boxu nemohou nastat žádná zalomení řádků. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Pokud tento prvek není specifikován, v boxu mohou nastat zalomení. Výchozí: true

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

Bez zalomení. Tato vlastnost určuje vlastnost "unbreakable" na objektovém boxu. Pokud je true, v boxu nemohou nastat žádná zalomení řádků. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Pokud tento prvek není specifikován, v boxu mohou nastat zalomení. Výchozí: true

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

Diferenciál. Pokud je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává odpovídající vodorovné odsazení pro matematický diferenciál. Výchozí: false

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

Diferenciál. Pokud je true, box funguje jako diferenciál (např. \\ud835\\udc51\\ud835\\udc65 v integrandu) a získává odpovídající vodorovné odsazení pro matematický diferenciál. Výchozí: false

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

Pokud je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí: false

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

Pokud je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí: false

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
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které má být použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení)

--------------------

> ```
> Example:
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

Explicitní zalomení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které má být použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Získat podřízené prvky

**Návratová hodnota:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vlastnosti řídících znaků

**Návratová hodnota:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps