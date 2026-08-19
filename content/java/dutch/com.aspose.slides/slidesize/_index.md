---
title: SlideSize
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de grootte en oriëntatie van een dia voor.
type: docs
url: /nl/com.aspose.slides/slidesize/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Stelt de grootte en oriëntatie van een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSize()](#getSize--) | Haalt de afmetingen van de dia op in punten. |
| [getType()](#getType--) | Haalt het dia-grootte-type op. |
| [getOrientation()](#getOrientation--) | Haalt de oriëntatie van de dia op of stelt deze in. |
| [setOrientation(int value)](#setOrientation-int-) | Haalt de oriëntatie van de dia op of stelt deze in. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Stelt de dia-grootte in op basis van type en schaalt bestaande inhoud. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Stelt de dia-afmetingen expliciet in en schaalt bestaande inhoud. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


Haalt de afmetingen van de dia op in punten.

--------------------

Het toewijzen van een nieuwe waarde reset de #getType.getType eigenschap naar [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) en stelt de #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) in.

**Retourwaarde:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```


Haalt het dia-grootte-type op.

--------------------

Het toewijzen van een waarde anders dan [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) past #getSize.getSize aan op basis van de vooraf gedefinieerde afmetingen, terwijl de huidige #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) behouden blijft.

**Retourwaarde:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Haalt de oriëntatie van de dia op of stelt deze in.

--------------------

Het wijzigen van deze waarde verwisselt de breedte en hoogte van de dia.

**Retourwaarde:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Haalt de oriëntatie van de dia op of stelt deze in.

--------------------

Het wijzigen van deze waarde verwisselt de breedte en hoogte van de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Stelt de dia-grootte in op basis van type en schaalt bestaande inhoud.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | De vooraf gedefinieerde dia-grootte die moet worden toegepast. |
| scaleType | int | De te gebruiken schaalmodus voor de inhoud. |

--------------------

Het toewijzen van een waarde anders dan [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) past #getSize.getSize aan op basis van het geselecteerde type, terwijl #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) behouden blijft. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Stelt de dia-afmetingen expliciet in en schaalt bestaande inhoud.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | float | De nieuwe dia-breedte, in punten. |
| height | float | De nieuwe dia-hoogte, in punten. |
| scaleType | int | De te gebruiken schaalmodus voor de inhoud. |

--------------------

Dit reset de #getType.getType eigenschap naar [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) en stelt de #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) in. |