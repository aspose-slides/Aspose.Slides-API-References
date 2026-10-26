---
title: IMathBox
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert de logische verpakking (boxing) van een wiskundig element.
type: docs
url: /nl/com.aspose.slides/imathbox/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specificeert de logische verpakking (boxing) van een wiskundig element. Bijvoorbeeld, een verpakt object kan dienen als een operator-emulator met of zonder een uitlijningspunt, fungeren als een regeleinde-markeerpunt, of gegroepeerd worden zodat geen regeleinden binnen worden toegestaan. Bijvoorbeeld, de "=="-operator moet verpakt worden om regeleinden te voorkomen.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator-emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator-emulator. |
| [getNoBreak()](#getNoBreak--) | Geen onderbreking. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Geen onderbreking. |
| [getDifferential()](#getDifferential--) | Differentiëel. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differentiëel. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen ermee worden uitgelijnd. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen ermee worden uitgelijnd. |
| [getExplicitBreak()](#getExplicitBreak--) | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het box-object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het box-object. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basisargument

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operator-emulator. Wanneer waar, gedragen de doos en de inhoud zich als één operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operators. Operator-emulators worden vaak gebruikt wanneer een of meer tekens gecombineerd worden tot een operator, zoals '=='. Standaardwaarde: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Retourwaarde:**
`boolean`
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operator-emulator. Wanneer waar, gedragen de doos en de inhoud zich als één operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operators. Operator-emulators worden vaak gebruikt wanneer een of meer tekens gecombineerd worden tot een operator, zoals '=='. Standaardwaarde: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | `boolean` |  |
### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap van het object-box. Wanneer waar, kunnen er binnen de box geen regeleinden optreden. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er wel regeleinden binnen de box optreden. Standaard: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Retourwaarde:**
`boolean`
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap van het object-box. Wanneer waar, kunnen er binnen de box geen regeleinden optreden. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er wel regeleinden binnen de box optreden. Standaard: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | `boolean` |  |
### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differentiëel. Wanneer waar, functioneert de doos als een differentiaal (bijvoorbeeld \\ud835\\udc51\\ud835\\udc65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Retourwaarde:**
`boolean`
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differentiëel. Wanneer waar, functioneert de doos als een differentiaal (bijvoorbeeld \\ud835\\udc51\\ud835\\udc65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | `boolean` |  |
### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen ermee worden uitgelijnd. Standaard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Retourwaarde:**
`boolean`
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen ermee worden uitgelijnd. Standaard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | `byte` |  |
### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het box-object. Bepaalt het nummer van de operator op de vorige regel wiskundige tekst die gebruikt moet worden als uitlijningspunt voor de huidige regel wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Retourwaarde:**
`byte`
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het box-object. Bepaalt het nummer van de operator op de vorige regel wiskundige tekst die gebruikt moet worden als uitlijningspunt voor de huidige regel wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | `byte` |  |