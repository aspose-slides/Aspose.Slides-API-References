---
title: SwfOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/swfoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Stellt Optionen bereit, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instanziieren Sie ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Speichern der Präsentation und der Notizseiten
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Standardkonstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [getCompressed()](#getCompressed--) | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. |
| [getViewerIncluded()](#getViewerIncluded--) | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. |
| [getShowPageBorder()](#getShowPageBorder--) | Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. |
| [getShowFullScreen()](#getShowFullScreen--) | Vollbildschaltfläche ein-/ausblenden. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Vollbildschaltfläche ein-/ausblenden. |
| [getShowPageStepper()](#getShowPageStepper--) | Seitenschrittschalter ein-/ausblenden. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Seitenschrittschalter ein-/ausblenden. |
| [getShowSearch()](#getShowSearch--) | Suchbereich ein-/ausblenden. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Suchbereich ein-/ausblenden. |
| [getShowTopPane()](#getShowTopPane--) | Gesamtes oberes Fenster ein-/ausblenden. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Gesamtes oberes Fenster ein-/ausblenden. |
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
| [getLogoLink()](#getLogoLink--) | Gibt die vollständige Hyperlink-Adresse für ein Logo zurück oder legt sie fest. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Gibt die vollständige Hyperlink-Adresse für ein Logo zurück oder legt sie fest. |
| [getJpegQuality()](#getJpegQuality--) | Gibt die Qualität von JPEG-Bildern an. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Gibt die Qualität von JPEG-Bildern an. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gibt den Modus an, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gibt den Modus an, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Standardkonstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Rückgabewert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Standardwert ist true.

**Rückgabewert:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. Standardwert ist true.

**Rückgabewert:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. Standardwert ist true.

**Rückgabewert:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Gibt an, ob ein Rahmen um die Seiten angezeigt werden soll. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Vollbildschaltfläche ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabewert:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Vollbildschaltfläche ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Seitenschrittschalter ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabewert:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Seitenschrittschalter ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Suchbereich ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabewert:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Suchbereich ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Ganzes oberes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabewert:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Ganzes oberes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Unteres Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabewert:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Unteres Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Linkes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Rückgabewert:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Linkes Fenster ein-/ausblenden. Kann in flashvars überschrieben werden. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Mit geöffnetem linkem Fenster starten. Kann in flashvars überschrieben werden. Standardwert ist false.

**Rückgabewert:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Mit geöffnetem linkem Fenster starten. Kann in flashvars überschrieben werden. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Kontextmenü aktivieren/deaktivieren. Standardwert ist true.

**Rückgabewert:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Kontextmenü aktivieren/deaktivieren. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Bild, das als Logo in der oberen rechten Ecke des Betrachters angezeigt wird. Bild muss ein 32 x 64 Pixel großes PNG sein, sonst kann das Logo falsch dargestellt werden.

**Rückgabewert:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Bild, das als Logo in der oberen rechten Ecke des Betrachters angezeigt wird. Bild muss ein 32 x 64 Pixel großes PNG sein, sonst kann das Logo falsch dargestellt werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Gibt die vollständige Hyperlink-Adresse für ein Logo zurück oder legt sie fest. Wirksam nur, wenn ein (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) angegeben ist.

**Rückgabewert:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Gibt die vollständige Hyperlink-Adresse für ein Logo zurück oder legt sie fest. Wirksam nur, wenn ein (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) angegeben ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Gibt die Qualität von JPEG-Bildern an. Standardwert ist 95.

**Rückgabewert:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Gibt die Qualität von JPEG-Bildern an. Standardwert ist 95.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Gibt den Modus an, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. Diese Eigenschaft unterstützt keine Zuweisung von Objekten vom Typ [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

**Rückgabewert:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Gibt den Modus an, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. Diese Eigenschaft unterstützt keine Zuweisung von Objekten vom Typ [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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