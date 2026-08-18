---
title: IXpsOptions
second_title: Aspose.Slides Java API referencia
description: Lehetőségeket biztosít, amelyek meghatározzák, hogyan menthető el egy prezentáció XPS formátumban.
type: docs
url: /hu/com.aspose.slides/ixpsoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Lehetőségeket biztosít, amelyek meghatározzák, hogyan menthető el egy prezentáció XPS formátumban.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, ha minden dia köré fekete keretet rajzol. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, ha minden dia köré fekete keretet rajzol. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. Olvasás/írás boolean.

--------------------

Alapértelmezés szerint **true**.

**Visszatérési érték:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. Olvasás/írás boolean.

--------------------

Alapértelmezés szerint **true**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, ha minden dia köré fekete keretet rajzol. Olvasás/írás boolean.

--------------------

Alapértelmezés szerint **false**.

**Visszatérési érték:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, ha minden dia köré fekete keretet rajzol. Olvasás/írás boolean.

--------------------

Alapértelmezés szerint **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezés szerint **false**.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezés szerint **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |