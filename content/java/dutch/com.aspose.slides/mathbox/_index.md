---
title: MathBox
second_title: Aspose.Slides voor Java API Referentie
description: Specificeert de logische verpakking (boxing) van een wiskundig element.
type: docs
url: /nl/com.aspose.slides/mathbox/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Specificeert de logische verpakking (boxing) van een wiskundig element. Bijvoorbeeld kan een verpakt object dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of gegroepeerd worden zodat regelbreuken binnenin niet zijn toegestaan. Bijvoorbeeld moet de "=="-operator verpakt worden om regelbreuken te voorkomen.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Initialiseert MathBox met het opgegeven element als argument |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operatoremulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operatoremulator. |
| [getNoBreak()](#getNoBreak--) | Geen breken Deze eigenschap specificeert de "ononderbreekbare" eigenschap van de objectbox. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Geen breken Deze eigenschap specificeert de "ononderbreekbare" eigenschap van de objectbox. |
| [getDifferential()](#getDifferential--) | Differentiaal Wanneer true, functioneert de doos als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integraal), en ontvangt de juiste horizontale ruimte voor het wiskundige differentiaal. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differentiaal Wanneer true, functioneert de doos als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integraal), en ontvangt de juiste horizontale ruimte voor het wiskundige differentiaal. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Wanneer true, dient deze operatoremulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen op dit punt worden uitgelijnd. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Wanneer true, dient deze operatoremulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen op dit punt worden uitgelijnd. |
| [getExplicitBreak()](#getExplicitBreak--) | Expliciete breuk specificeert of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het box-object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Expliciete breuk specificeert of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het box-object. |
| [getChildren()](#getChildren--) | Haal kindelementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Eigenschappen van besturingstekens |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Initialiseert MathBox met het opgegeven element als argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waarop de box wordt toegepast. Kan null zijn. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```


**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Operatoremulator. Wanneer true, gedragen de doos en de inhoud zich als één enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren. Operatoremulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Retourwaarde:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Operatoremulator. Wanneer true, gedragen de doos en de inhoud zich als één enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren. Operatoremulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


Geen breuk Deze eigenschap specificeert de "ononderbreekbare" eigenschap van de objectbox. Wanneer true, kunnen er geen regelbreuken optreden binnen de doos. Dit kan belangrijk zijn voor operatoremulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is opgegeven, kunnen er breuken optreden binnen de doos. Standaard: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Retourwaarde:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


Geen breuk Deze eigenschap specificeert de "ononderbreekbare" eigenschap van de objectbox. Wanneer true, kunnen er geen regelbreuken optreden binnen de doos. Dit kan belangrijk zijn voor operatoremulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is opgegeven, kunnen er breuken optreden binnen de doos. Standaard: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Differentiaal Wanneer true, functioneert de doos als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integraal), en ontvangt de juiste horizontale ruimte voor het wiskundige differentiaal. Standaard: false

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
public final void setDifferential(boolean value)
```


Differentiaal Wanneer true, functioneert de doos als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integraal), en ontvangt de juiste horizontale ruimte voor het wiskundige differentiaal. Standaard: false

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
public final boolean getAlignmentPoint()
```


Wanneer true, dient deze operatoremulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen op dit punt worden uitgelijnd. Standaard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Retourwaarde:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Wanneer true, dient deze operatoremulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen op dit punt worden uitgelijnd. Standaard: false

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
public final byte getExplicitBreak()
```


Expliciete breuk specificeert of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het box-object. Specificeert het nummer van de operator op de vorige regel wiskundige tekst die als uitlijningspunt voor de huidige regel wiskundige tekst dient. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete breuk)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Retourwaarde:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```


Expliciete breuk specificeert of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het box-object. Specificeert het nummer van de operator op de vorige regel wiskundige tekst die als uitlijningspunt voor de huidige regel wiskundige tekst dient. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete breuk)

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
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haal kindelementen op

**Retourwaarde:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Eigenschappen van besturingstekens

**Retourwaarde:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps