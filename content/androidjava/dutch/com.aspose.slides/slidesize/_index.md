---
title: SlideSize
second_title: Aspose.Slides voor Android via Java API-referentie
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
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getSize()](#getSize--) | Haalt de dia-afmetingen op in punten. |
| [getType()](#getType--) | Haalt het dia-grootte type op. |
| [getOrientation()](#getOrientation--) | Haalt of stelt de dia-oriëntatie in. |
| [setOrientation(int value)](#setOrientation-int-) | Haalt of stelt de dia-oriëntatie in. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Stelt de dia-grootte in op basis van type en schaalt bestaande inhoud. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Stelt de dia-afmetingen expliciet in en schaalt bestaande inhoud. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


Haalt de dia-afmetingen op in punten.

--------------------

Een nieuwe waarde toewijzen zet de \#getType.getType eigenschap terug naar [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) en stelt de \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) in.

**Retour:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


Haalt het dia-grootte type op.

--------------------

Een waarde toewijzen die anders is dan [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) past de \#getSize.getSize aan volgens de vooraf gedefinieerde afmetingen, terwijl de huidige \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) behouden blijft.

**Retour:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Haalt of stelt de dia-oriëntatie in.

--------------------

Het wijzigen van deze waarde wisselt de breedte en hoogte van de dia.

**Retour:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Haalt of stelt de dia-oriëntatie in.

--------------------

Het wijzigen van deze waarde wisselt de breedte en hoogte van de dia.

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
| scaleType | int | De te gebruiken inhoud-schaalmodus. |

--------------------

Een waarde toewijzen die anders is dan [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) past de \#getSize.getSize aan op basis van het geselecteerde type, terwijl \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) behouden blijft. |
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
| scaleType | int | De te gebruiken inhoud-schaalmodus. |

--------------------

Dit zet de \#getType.getType eigenschap terug naar [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) en stelt de \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) in. |