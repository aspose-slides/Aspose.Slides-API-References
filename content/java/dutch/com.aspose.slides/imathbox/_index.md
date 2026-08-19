---
title: IMathBox
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert de logische verpakking (boxing) van een wiskundig element.
type: docs
url: /nl/com.aspose.slides/imathbox/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specificeert de logische verpakking (boxing) van een wiskundig element. Bijvoorbeeld, een ingesloten object kan fungeren als een operatoremulator met of zonder uitlijningspunt, als een regeleinde-punt, of gegroepeerd worden zodat er geen regeleinden binnen worden toegestaan. Bijvoorbeeld, de "=="-operator moet ingesloten worden om regeleinden te voorkomen.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operatoremulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operatoremulator. |
| [getNoBreak()](#getNoBreak--) | Geen onderbreking. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Geen onderbreking. |
| [getDifferential()](#getDifferential--) | Differentiaal. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differentiaal. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Wanneer true, fungeert deze operatoremulator als een uitlijningspunt; dat wil zeggen dat aangewezen uitlijningspunten in andere vergelijkingen ermee uitgelijnd kunnen worden. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Wanneer true, fungeert deze operatoremulator als een uitlijningspunt; dat wil zeggen dat aangewezen uitlijningspunten in andere vergelijkingen ermee uitgelijnd kunnen worden. |
| [getExplicitBreak()](#getExplicitBreak--) | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het Box-object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het Box-object. |
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


Operatoremulator. Wanneer true, gedragen de box en de inhoud zich als één enkele operator en erven de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren. Standaardwaarde: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Retourwaarde:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```


Operatoremulator. Wanneer true, gedragen de box en de inhoud zich als één enkele operator en erven de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren. Standaardwaarde: false

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
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```


Geen onderbreking. Deze eigenschap specificeert de “ononderbroken”-eigenschap van het object-box. Wanneer true, kunnen er geen regeleinden binnen de box optreden. Dit kan belangrijk zijn voor operatoremulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er regeleinden binnen de box optreden. Standaard: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Retourwaarde:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```


Geen onderbreking. Deze eigenschap specificeert de “ononderbroken”-eigenschap van het object-box. Wanneer true, kunnen er geen regeleinden binnen de box optreden. Dit kan belangrijk zijn voor operatoremulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er regeleinden binnen de box optreden. Standaard: true

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
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```


Differentiaal. Wanneer true, gedraagt de box zich als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integrand), en krijgt de juiste horizontale ruimte voor het wiskundige differentiaal. Standaard: false

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
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```


Differentiaal. Wanneer true, gedraagt de box zich als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integrand), en krijgt de juiste horizontale ruimte voor het wiskundige differentiaal. Standaard: false

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
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```


Wanneer true, fungeert deze operatoremulator als een uitlijningspunt; dat wil zeggen dat aangewezen uitlijningspunten in andere vergelijkingen ermee uitgelijnd kunnen worden. Standaard: false

--------------------

> ```
> Voorbeeld:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Retourwaarde:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```


Wanneer true, fungeert deze operatoremulator als een uitlijningspunt; dat wil zeggen dat aangewezen uitlijningspunten in andere vergelijkingen ermee uitgelijnd kunnen worden. Standaard: false

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
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```


Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het Box-object. Geeft het aantal van de operator op de vorige regel wiskundige tekst dat moet worden gebruikt als uitlijningspunt voor de huidige regel wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

--------------------

> ```
> Voorbeeld:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Retourwaarde:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```


Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het Box-object. Geeft het aantal van de operator op de vorige regel wiskundige tekst dat moet worden gebruikt als uitlijningspunt voor de huidige regel wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

--------------------

> ```
> Voorbeeld:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |