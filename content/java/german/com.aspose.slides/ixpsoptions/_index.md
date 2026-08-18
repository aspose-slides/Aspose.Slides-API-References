---
title: IXpsOptions
second_title: Aspose.Slides für Java API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im XPS-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/ixpsoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Bietet Optionen, die steuern, wie eine Präsentation im XPS-Format gespeichert wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, um um jede Folie einen schwarzen Rahmen zu zeichnen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, um um jede Folie einen schwarzen Rahmen zu zeichnen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. Lese-/Schreib- boolean.

--------------------

Standard ist **true**.

**Rückgabewert:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. Lese-/Schreib- boolean.

--------------------

Standard ist **true**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, um um jede Folie einen schwarzen Rahmen zu zeichnen. Lese-/Schreib- boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, um um jede Folie einen schwarzen Rahmen zu zeichnen. Lese-/Schreib- boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. Standard ist **false**.

**Rückgabewert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |