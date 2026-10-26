---
title: MathBox
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert de logische verpakking (boxing) van een wiskundig element.
type: docs
url: /nl/com.aspose.slides/mathbox/
---
**Erfelijkheid:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Specificeert de logische verpakking (boxing) van een wiskundig element. Bijvoorbeeld, een verpakt object kan dienen als een operator-emulator met of zonder een uitlijningspunt, kan dienen als een regeleinde-punt, of kan gegroepeerd worden zodat geen regeleinden binnen het object zijn toegestaan. Bijvoorbeeld, de "==" operator moet verpakt worden om regeleinden te voorkomen.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Initialiseert MathBox met het opgegeven element als argument |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator-emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator-emulator. |
| [getNoBreak()](#getNoBreak--) | Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap op de objectbox. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap op de objectbox. |
| [getDifferential()](#getDifferential--) | Differentiaal. Wanneer waar, functioneert de box als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integrand), en krijgt de juiste horizontale spatiëring voor de wiskundige differentiaal. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differentiaal. Wanneer waar, functioneert de box als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integrand), en krijgt de juiste horizontale spatiëring voor de wiskundige differentiaal. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen hiermee worden uitgelijnd. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen hiermee worden uitgelijnd. |
| [getExplicitBreak()](#getExplicitBreak--) | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel omslaat aan het begin van het box-object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel omslaat aan het begin van het box-object. |
| [getChildren()](#getChildren--) | Haal kindelementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character-eigenschappen |
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

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Operator-emulator. Wanneer waar, gedragen de box en de inhoud zich als één enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operators. Operator-emulators worden vaak gebruikt wanneer één of meer glyfen samen een operator vormen, zoals '=='. Standaardwaarde: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Retour:** boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Operator-emulator. Wanneer waar, gedragen de box en de inhoud zich als één enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operators. Operator-emulators worden vaak gebruikt wanneer één of meer glyfen samen een operator vormen, zoals '=='. Standaardwaarde: false

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

Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap op de objectbox. Wanneer waar, kunnen er geen regeleinden binnen de box optreden. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er onderbrekingen binnen de box optreden. Standaard: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Retour:** boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap op de objectbox. Wanneer waar, kunnen er geen regeleinden binnen de box optreden. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er onderbrekingen binnen de box optreden. Standaard: true

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

Differentiaal. Wanneer waar, functioneert de box als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integrand), en krijgt de juiste horizontale spatiëring voor de wiskundige differentiaal. Standaard: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Retour:** boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

Differentiaal. Wanneer waar, functioneert de box als een differentiaal (bijv. \\ud835\\udc51\\ud835\\udc65 in een integrand), en krijgt de juiste horizontale spatiëring voor de wiskundige differentiaal. Standaard: false

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

Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen hiermee worden uitgelijnd. Standaard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Retour:** boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

Wanneer waar, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen hiermee worden uitgelijnd. Standaard: false

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

Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel omslaat aan het begin van het box-object. Bepaalt het nummer van de operator op de vorige regel wiskundige tekst die als uitlijningspunt voor de huidige regel moet dienen; mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Retour:** byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel omslaat aan het begin van het box-object. Bepaalt het nummer van de operator op de vorige regel wiskundige tekst die als uitlijningspunt voor de huidige regel moet dienen; mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

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

**Retour:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character-eigenschappen

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps