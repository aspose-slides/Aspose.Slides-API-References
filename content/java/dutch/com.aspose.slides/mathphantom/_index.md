---
title: MathPhantom
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een phantom wiskundig object ltmphantgt voor dat de lay-out van het onderliggende element beïnvloedt zonder het noodzakelijkerwijs weer te geven.
type: docs
url: /nl/com.aspose.slides/mathphantom/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Stelt een phantom wiskundig object (<m:phant>) voor dat de lay-out van het onderliggende element beïnvloedt zonder het noodzakelijkerwijs weer te geven. Een phantom kan de basisuitdrukking verbergen terwijl het zijn breedte, hoogte of diepte behoudt om formules uit te lijnen of ruimte te reserveren. Zichtbaarheid en geometrisch gedrag worden gecontroleerd door eigenschappen zoals Show, ZeroWid, ZeroAsc, ZeroDesc en Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Verberg de inhoud
>  phantom.setZeroWidth(false);     // Behoud de breedte
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de class [MathPhantom](../../com.aspose.slides/mathphantom) met het opgegeven basismath-element. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getShow()](#getShow--) | Haalt een waarde op of stelt deze in die aangeeft of het basiselement wordt weergegeven. |
| [setShow(boolean value)](#setShow-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of het basiselement wordt weergegeven. |
| [getZeroWidth()](#getZeroWidth--) | Haalt een waarde op of stelt deze in die aangeeft of de breedte van het basiselement als nul moet worden behandeld. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de breedte van het basiselement als nul moet worden behandeld. |
| [getZeroAsc()](#getZeroAsc--) | Haalt een waarde op of stelt deze in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld. |
| [getZeroDesc()](#getZeroDesc--) | Haalt een waarde op of stelt deze in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld. |
| [getTransp()](#getTransp--) | Haalt een waarde op of stelt deze in die aangeeft of de phantom transparant is voor class-gebaseerde spatieregels. |
| [setTransp(boolean value)](#setTransp-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de phantom transparant is voor class-gebaseerde spatieregels. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | Haal kinderen elementen op |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```


Initialiseert een nieuw exemplaar van de [MathPhantom](../../com.aspose.slides/mathphantom) class met het opgegeven basismath-element.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement [IMathElement](../../com.aspose.slides/imathelement) waarvan de zichtbaarheid en lay-out worden gecontroleerd door de phantom. Dit element definieert de inhoud die verborgen of getoond kan worden, terwijl het nog steeds de geometrische uitlijning van de omringende wiskunde beïnvloedt. |

--------------------

Het phantom-element wordt gebruikt om de visuele ruimte van de basisuitdrukking te reserveren of te onderdrukken zonder deze noodzakelijkerwijs weer te geven. Het komt overeen met het OMML-element <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```


Haalt een waarde op of stelt deze in die aangeeft of het basiselement wordt weergegeven.

--------------------

Wanneer false, is het basiselement verborgen maar kan nog steeds ruimte innemen afhankelijk van andere phantom-instellingen. Komt overeen met het OMML-attribuut m:show.

**Retour:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of het basiselement wordt weergegeven.

--------------------

Wanneer false, is het basiselement verborgen maar kan nog steeds ruimte innemen afhankelijk van andere phantom-instellingen. Komt overeen met het OMML-attribuut m:show.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```


Haalt een waarde op of stelt deze in die aangeeft of de breedte van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, reserveert de phantom geen horizontale ruimte voor zijn basis. Komt overeen met het OMML-attribuut m:zeroWid.

**Retour:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de breedte van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, reserveert de phantom geen horizontale ruimte voor zijn basis. Komt overeen met het OMML-attribuut m:zeroWid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```


Haalt een waarde op of stelt deze in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verhoogt de phantom de basislijn van de omringende wiskunderegel niet. Komt overeen met het OMML-attribuut m:zeroAsc.

**Retour:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verhoogt de phantom de basislijn van de omringende wiskunderegel niet. Komt overeen met het OMML-attribuut m:zeroAsc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Haalt een waarde op of stelt deze in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verlaagt de phantom de basislijn van de omringende wiskunderegel niet. Komt overeen met het OMML-attribuut m:zeroDesc.

**Retour:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verlaagt de phantom de basislijn van de omringende wiskunderegel niet. Komt overeen met het OMML-attribuut m:zeroDesc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Haalt een waarde op of stelt deze in die aangeeft of de phantom transparant is voor class-gebaseerde spatieregels.

--------------------

Wanneer true, beïnvloeden operatoren en symbolen binnen de phantom nog steeds de wiskundige spatiëring rond de phantom (alsof deze zichtbaar is). Wanneer false, worden class-gebaseerde spatieregels genegeerd. Komt overeen met het OMML-attribuut m:transp.

**Retour:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de phantom transparant is voor class-gebaseerde spatieregels.

--------------------

Wanneer true, beïnvloeden operatoren en symbolen binnen de phantom nog steeds de wiskundige spatiëring rond de phantom (alsof deze zichtbaar is). Wanneer false, worden class-gebaseerde spatieregels genegeerd. Komt overeen met het OMML-attribuut m:transp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haalt kinderen elementen op

**Retour:**
com.aspose.slides.IMathElement[]