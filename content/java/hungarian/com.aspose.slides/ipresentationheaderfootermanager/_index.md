---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides Java API referenciája
description: A prezentáció összes lábléc, dátum-idő és oldalszám helyőrzőjének viselkedését kezelő menedzsert képviseli.
type: docs
url: /hu/com.aspose.slides/ipresentationheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

A menedzsert reprezentálja, amely a prezentáció összes lábléc, dátum-idő és oldalszám helyőrzőjének viselkedését tartalmazza.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Megváltoztatja az összes fejléc helyőrző láthatóságát, beleértve a notes mastert, a notes slide-okat és a handout mastert. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Megváltoztatja az összes lábléc helyőrző láthatóságát, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Megváltoztatja az összes oldalszám helyőrző láthatóságát, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Megváltoztatja az összes dátum-idő helyőrző láthatóságát, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Beállítja a szöveget az összes fejléc helyőrzőhöz, beleértve a notes mastert, a notes slide-okat és a handout mastert. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Beállítja a szöveget az összes lábléc helyőrzőhöz, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Beállítja a szöveget az összes dátum-idő helyőrzőhöz, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Megváltoztatja a lábléc, dátum-idő és oldalszám helyőrzők láthatóságát minden címdial és az első layout dián. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```


Megváltoztatja az összes fejléc helyőrző láthatóságát, beleértve a notes mastert, a notes slide-okat és a handout mastert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a fejléc helyőrzőket, egyébként elrejti őket. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```


Megváltoztatja az összes lábléc helyőrző láthatóságát, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a lábléc helyőrzőket, egyébként elrejti őket. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```


Megváltoztatja az összes oldalszám helyőrző láthatóságát, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi az oldalszám helyőrzőket, egyébként elrejti őket. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```


Megváltoztatja az összes dátum-idő helyőrző láthatóságát, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a dátum-idő helyőrzőket, egyébként elrejti őket. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```


Beállítja a szöveget az összes fejléc helyőrzőhöz, beleértve a notes mastert, a notes slide-okat és a handout mastert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```


Beállítja a szöveget az összes lábléc helyőrzőhöz, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```


Beállítja a szöveget az összes dátum-idő helyőrzőhöz, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```


Megváltoztatja a lábléc, dátum-idő és oldalszám helyőrzők láthatóságát minden címdial és az első layout dián. Title slides \\u2013 slides based on first layout slide (regardless of type of this first layout).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a helyőrzőket, egyébként elrejti őket. |