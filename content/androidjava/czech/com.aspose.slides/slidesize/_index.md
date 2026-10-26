---
title: SlideSize
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Representuje velikost a orientaci snímku.
type: docs
url: /cs/com.aspose.slides/slidesize/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Reprezentuje velikost a orientaci snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getSize()](#getSize--) | Získá rozměry snímku v bodech. |
| [getType()](#getType--) | Získá typ velikosti snímku. |
| [getOrientation()](#getOrientation--) | Získá nebo nastaví orientaci snímku. |
| [setOrientation(int value)](#setOrientation-int-) | Získá nebo nastaví orientaci snímku. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Nastaví velikost snímku podle typu a přizpůsobí existující obsah. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Nastaví rozměry snímku explicitně a přizpůsobí existující obsah. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


Získá rozměry snímku v bodech.

--------------------

Přiřazením nové hodnoty se resetuje vlastnost \#getType.getType na [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) a nastaví se \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Vrací:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


Získá typ velikosti snímku.

--------------------

Přiřazením jakékoli hodnoty jinak než [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) se upraví \#getSize.getSize podle předdefinovaných rozměrů, přičemž se zachová aktuální \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Vrací:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Získá nebo nastaví orientaci snímku.

--------------------

Změnou této hodnoty se prohodí šířka a výška snímku.

**Vrací:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Získá nebo nastaví orientaci snímku.

--------------------

Změnou této hodnoty se prohodí šířka a výška snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Nastaví velikost snímku podle typu a přizpůsobí existující obsah.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Předdefinovaná velikost snímku, která se použije. |
| scaleType | int | Režim škálování obsahu, který se použije. |

--------------------

Přiřazením jakékoli hodnoty jinak než [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) se upraví \#getSize.getSize podle vybraného typu, přičemž se zachová \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Nastaví rozměry snímku explicitně a přizpůsobí existující obsah.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | float | Nová šířka snímku v bodech. |
| height | float | Nová výška snímku v bodech. |
| scaleType | int | Režim škálování obsahu, který se použije. |

--------------------

Toto resetuje vlastnost \#getType.getType na [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) a nastaví \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |