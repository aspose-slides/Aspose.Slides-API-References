---
title: ISwfOptions
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im SWF-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/iswfoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Stellt Optionen bereit, die steuern, wie eine Präsentation im SWF-Format gespeichert wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. |
| [getViewerIncluded()](#getViewerIncluded--) | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. |
| [getShowPageBorder()](#getShowPageBorder--) | Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [getShowFullScreen()](#getShowFullScreen--) | Vollbild-Button ein-/ausblenden. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Vollbild-Button ein-/ausblenden. |
| [getShowPageStepper()](#getShowPageStepper--) | Seiten-Stepper ein-/ausblenden. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Seiten-Stepper ein-/ausblenden. |
| [getShowSearch()](#getShowSearch--) | Suchbereich ein-/ausblenden. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Suchbereich ein-/ausblenden. |
| [getShowTopPane()](#getShowTopPane--) | Ganzes oberes Fenster ein-/ausblenden. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Ganzes oberes Fenster ein-/ausblenden. |
| [getShowBottomPane()](#getShowBottomPane--) | Unteres Fenster ein-/ausblenden. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Unteres Fenster ein-/ausblenden. |
| [getShowLeftPane()](#getShowLeftPane--) | Linkes Fenster ein-/ausblenden. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Linkes Fenster ein-/ausblenden. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Mit geöffnetem linkem Fenster starten. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Mit geöffnetem linkem Fenster starten. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Kontextmenü aktivieren/deaktivieren. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Kontextmenü aktivieren/deaktivieren. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Bild, das als Logo in der oberen rechten Ecke des Betrachters angezeigt wird. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Bild, das als Logo in der oberen rechten Ecke des Betrachters angezeigt wird. |
| [getLogoLink()](#getLogoLink--) | Ruft die vollständige Hyperlink-Adresse für ein Logo ab oder legt sie fest. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Ruft die vollständige Hyperlink-Adresse für ein Logo ab oder legt sie fest. |
| [getJpegQuality()](#getJpegQuality--) | Gibt die Qualität von JPEG-Bildern an. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Gibt die Qualität von JPEG-Bildern an. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gibt den Modus an, in dem Folien beim Exportieren einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gibt den Modus an, in dem Folien beim Exportieren einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Standardwert ist true.

**Rückgabe:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. Standardwert ist true.

**Rückgabe:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. Standardwert ist true.

**Rückgabe:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist false.

**Rückgabe:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Vollbild-Button ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabe:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Vollbild-Button ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Seiten-Stepper ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabe:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Seiten-Stepper ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Suchbereich ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabe:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Suchbereich ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Ganzes oberes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabe:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Ganzes oberes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Unteres Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabe:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Unteres Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Linkes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabe:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Linkes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Mit geöffnetem linkem Fenster starten. Kann in flashvars überschrieben werden. Standardwert ist false.

**Rückgabe:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Mit geöffnetem linkem Fenster starten. Kann in flashvars überschrieben werden. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Kontextmenü aktivieren/deaktivieren. Standardwert ist true.

**Rückgabe:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Kontextmenü aktivieren/deaktivieren. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Bild, das als Logo in der oberen rechten Ecke des Betrachters angezeigt wird. Das Bild sollte ein 32x64-Pixel-PNG sein, sonst kann das Logo fehlerhaft dargestellt werden.

**Rückgabe:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Bild, das als Logo in der oberen rechten Ecke des Betrachters angezeigt wird. Das Bild sollte ein 32x64-Pixel-PNG sein, sonst kann das Logo fehlerhaft dargestellt werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Ruft die vollständige Hyperlink-Adresse für ein Logo ab oder legt sie fest. Hat nur Wirkung, wenn ein (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) angegeben ist.

**Rückgabe:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Ruft die vollständige Hyperlink-Adresse für ein Logo ab oder legt sie fest. Hat nur Wirkung, wenn ein (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) angegeben ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Gibt die Qualität von JPEG-Bildern an. Standardwert ist 95.

**Rückgabe:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Gibt die Qualität von JPEG-Bildern an. Standardwert ist 95.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ruft den Modus ab oder legt ihn fest, in dem Folien beim Exportieren einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. Diese Eigenschaft unterstützt das Zuweisen von Objekten des Typs [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) nicht.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Ruft den Modus ab oder legt ihn fest, in dem Folien beim Exportieren einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. Diese Eigenschaft unterstützt das Zuweisen von Objekten des Typs [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) nicht.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |