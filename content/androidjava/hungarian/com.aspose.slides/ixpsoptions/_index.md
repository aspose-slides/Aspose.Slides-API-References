---
title: IXpsOptions
second_title: Aspose.Slides Androidra Java API hivatkozással
description: Olyan beállításokat biztosít, amelyek szabályozzák, hogy a prezentáció XPS formátumban hogyan legyen mentve.
type: docs
url: /hu/com.aspose.slides/ixpsoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik a bemutató XPS formátumban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Igaz, ha az összes prezentációban használt metafájlt PNG képekké konvertálja. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Igaz, ha az összes prezentációban használt metafájlt PNG képekké konvertálja. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Igaz, ha minden diára fekete keretet rajzol. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Igaz, ha minden diára fekete keretet rajzol. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

Igaz, ha az összes prezentációban használt metafájlt PNG képekké konvertálja. Olvasási/írási logikai érték.

--------------------

Az alapértelmezett **true**.

**Visszatérési érték:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Igaz, ha az összes prezentációban használt metafájlt PNG képekké konvertálja. Olvasási/írási logikai érték.

--------------------

Az alapértelmezett **true**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Igaz, ha minden diára fekete keretet rajzol. Olvasási/írási logikai érték.

--------------------

Az alapértelmezett **false**.

**Visszatérési érték:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Igaz, ha minden diára fekete keretet rajzol. Olvasási/írási logikai érték.

--------------------

Az alapértelmezett **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Az alapértelmezett **false**.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Az alapértelmezett **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |