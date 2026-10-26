---
title: IMathPhantom
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een phantom-wiskundig object ltmphantgt voor dat de lay-out van zijn kindelement beïnvloedt zonder het noodzakelijkerwijs weer te geven.
type: docs
url: /nl/com.aspose.slides/imathphantom/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Stelt een phantom wiskundig object (<m:phant>) voor dat de lay-out van zijn kindelement beïnvloedt zonder het noodzakelijkerwijs weer te geven. Een phantom kan zijn basisexpressie verbergen terwijl hij de breedte, hoogte of diepte behoudt om formules uit te lijnen of ruimte gereserveerd te houden. Zichtbaarheid en geometrisch gedrag worden geregeld door eigenschappen zoals Show, ZeroWid, ZeroAsc, ZeroDesc en Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Verberg de inhoud
>  phantom.setZeroWidth(false);     // Houd de breedte
>  ```

## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getShow()](#getShow--) | Geeft een waarde terug of stelt een waarde in die aangeeft of het basiselement wordt weergegeven. |
| [setShow(boolean value)](#setShow-boolean-) | Geeft een waarde terug of stelt een waarde in die aangeeft of het basiselement wordt weergegeven. |
| [getZeroWidth()](#getZeroWidth--) | Geeft een waarde terug of stelt een waarde in die aangeeft of de breedte van het basiselement als nul moet worden behandeld. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Geeft een waarde terug of stelt een waarde in die aangeeft of de breedte van het basiselement als nul moet worden behandeld. |
| [getZeroAsc()](#getZeroAsc--) | Geeft een waarde terug of stelt een waarde in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Geeft een waarde terug of stelt een waarde in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld. |
| [getZeroDesc()](#getZeroDesc--) | Geeft een waarde terug of stelt een waarde in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Geeft een waarde terug of stelt een waarde in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld. |
| [getTransp()](#getTransp--) | Geeft een waarde terug of stelt een waarde in die aangeeft of de phantom transparant is voor klassen-gebaseerde spatiëringsregels. |
| [setTransp(boolean value)](#setTransp-boolean-) | Geeft een waarde terug of stelt een waarde in die aangeeft of de phantom transparant is voor klassen-gebaseerde spatiëringsregels. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract boolean getShow()
```

Geeft een waarde terug of stelt een waarde in die aangeeft of het basiselement wordt weergegeven.

--------------------

Wanneer false, wordt het basiselement verborgen maar kan het nog steeds ruimte innemen afhankelijk van andere phantom-instellingen. Komt overeen met het OMML-attribuut m:show.

**Retour:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Geeft een waarde terug of stelt een waarde in die aangeeft of het basiselement wordt weergegeven.

--------------------

Wanneer false, wordt het basiselement verborgen maar kan het nog steeds ruimte innemen afhankelijk van andere phantom-instellingen. Komt overeen met het OMML-attribuut m:show.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de breedte van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, reserveert de phantom geen horizontale ruimte voor zijn basis. Komt overeen met het OMML-attribuut m:zeroWid.

**Retour:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de breedte van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, reserveert de phantom geen horizontale ruimte voor zijn basis. Komt overeen met het OMML-attribuut m:zeroWid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verhoogt de phantom de basislijn van de omringende wiskundige regel niet. Komt overeen met het OMML-attribuut m:zeroAsc.

**Retour:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verhoogt de phantom de basislijn van de omringende wiskundige regel niet. Komt overeen met het OMML-attribuut m:zeroAsc.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verlaagt de phantom de basislijn van de omringende wiskundige regel niet. Komt overeen met het OMML-attribuut m:zeroDesc.

**Retour:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld.

--------------------

Wanneer true, verlaagt de phantom de basislijn van de omringende wiskundige regel niet. Komt overeen met het OMML-attribuut m:zeroDesc.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de phantom transparant is voor klassen-gebaseerde spatiëringsregels.

--------------------

Wanneer true, beïnvloeden operatoren en symbolen binnen de phantom nog steeds de wiskundige spatiëring rond de phantom (alsof ze zichtbaar zijn). Wanneer false, worden klassen-gebaseerde spatiëringsregels genegeerd. Komt overeen met het OMML-attribuut m:transp.

**Retour:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Geeft een waarde terug of stelt een waarde in die aangeeft of de phantom transparant is voor klassen-gebaseerde spatiëringsregels.

--------------------

Wanneer true, beïnvloeden operatoren en symbolen binnen de phantom nog steeds de wiskundige spatiëring rond de phantom (alsof ze zichtbaar zijn). Wanneer false, worden klassen-gebaseerde spatiëringsregels genegeerd. Komt overeen met het OMML-attribuut m:transp.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |