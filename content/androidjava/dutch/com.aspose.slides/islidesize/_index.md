---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt de grootte en oriëntatie van een dia voor.
type: docs
url: /nl/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Stelt de grootte en oriëntatie van een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSize()](#getSize--) | Haalt de afmetingen van de dia op in punten. |
| [getType()](#getType--) | Haalt het type diaformaat op. |
| [getOrientation()](#getOrientation--) | Haalt de dia-oriëntatie op of stelt deze in. |
| [setOrientation(int value)](#setOrientation-int-) | Haalt de dia-oriëntatie op of stelt deze in. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Stelt de dia-grootte in op basis van type en schaalt bestaande inhoud. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Stelt de dia-afmetingen expliciet in en schaalt bestaande inhoud. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


Haalt de afmetingen van de dia op in punten.

--------------------

Het toewijzen van een nieuwe waarde reset de \#getType.getType eigenschap naar [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) en stelt de \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) in.

**Retour:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```


Haalt het type diaformaat op.

--------------------

Het toewijzen van een waarde anders dan [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) past de \#getSize.getSize aan volgens de vooraf gedefinieerde afmetingen, terwijl de huidige \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) behouden blijft.

**Retour:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Haalt de dia-oriëntatie op of stelt deze in.

--------------------

Het wijzigen van deze waarde verwisselt de breedte en hoogte van de dia.

**Retour:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Haalt de dia-oriëntatie op of stelt deze in.

--------------------

Het wijzigen van deze waarde verwisselt de breedte en hoogte van de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Stelt de dia-grootte in op basis van type en schaalt bestaande inhoud.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | De vooraf gedefinieerde dia-grootte die moet worden toegepast. |
| scaleType | int | De te gebruiken inhoud-schaalmodus. |

--------------------

Het toewijzen van een waarde anders dan [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) past de \#getSize.getSize aan op basis van het geselecteerde type, terwijl de \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) behouden blijft. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Stelt de dia-afmetingen expliciet in en schaalt bestaande inhoud.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | float | De nieuwe dia-breedte, in punten. |
| height | float | De nieuwe dia-hoogte, in punten. |
| scaleType | int | De te gebruiken inhoud-schaalmodus. |

--------------------

Dit reset de \#getType.getType eigenschap naar [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) en stelt de \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) in. |