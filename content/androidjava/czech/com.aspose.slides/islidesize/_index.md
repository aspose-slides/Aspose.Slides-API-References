---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /cs/com.aspose.slides/islidesize/
---```
public interface ISlideSize
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
public abstract SizeF getSize()
```


Získá rozměry snímku v bodech.

--------------------

Při přiřazení nové hodnoty se resetuje vlastnost \#getType.getType na [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) a nastaví se \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Vrací:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```


Získá typ velikosti snímku.

--------------------

Při přiřazení jakékoli hodnoty jinak než [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) se upraví \#getSize.getSize podle předdefinovaných rozměrů, přičemž se zachová aktuální \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Vrací:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Získá nebo nastaví orientaci snímku.

--------------------

Změna této hodnoty prohodí šířku a výšku snímku.

**Vrací:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Získá nebo nastaví orientaci snímku.

--------------------

Změna této hodnoty prohodí šířku a výšku snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Nastaví velikost snímku podle typu a přizpůsobí existující obsah.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Předdefinovaná velikost snímku, která se použije. |
| scaleType | int | Režim škálování obsahu, který se použije. |

--------------------

Při přiřazení jakékoli hodnoty jinak než [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) se upraví \#getSize.getSize podle vybraného typu, při zachování \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Nastaví rozměry snímku explicitně a přizpůsobí existující obsah.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | float | Nová šířka snímku v bodech. |
| height | float | Nová výška snímku v bodech. |
| scaleType | int | Režim škálování obsahu, který se použije. |

--------------------

Toto resetuje vlastnost \#getType.getType na [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) a nastaví \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |