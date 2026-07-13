---
title: IXpsOptions
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu XPS.
type: docs
url: /cs/com.aspose.slides/ixpsoptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu XPS.
## Metody

| Metoda | Popis |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True pro konverzi všech metafilů použité v prezentaci na PNG obrázky. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True pro konverzi všech metafilů použité v prezentaci na PNG obrázky. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True pro vykreslení černého rámu kolem každého snímku. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True pro vykreslení černého rámu kolem každého snímku. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


True pro konverzi všech metafilů použité v prezentaci na PNG obrázky. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **true**.

**Vrací:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


True pro konverzi všech metafilů použité v prezentaci na PNG obrázky. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **true**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


True pro vykreslení černého rámu kolem každého snímku. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


True pro vykreslení černého rámu kolem každého snímku. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |