---
title: SwfOptions
second_title: Aspose.Slides for Java API Referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Swf-formaat.
type: docs
url: /nl/com.aspose.slides/swfoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Swf-formaat.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Opslaan van presentatie en notitiepagina's
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Standaardconstructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getCompressed()](#getCompressed--) | Specificeert of het gegenereerde SWF-document moet worden gecomprimeerd of niet. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Specificeert of het gegenereerde SWF-document moet worden gecomprimeerd of niet. |
| [getViewerIncluded()](#getViewerIncluded--) | Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. |
| [getShowPageBorder()](#getShowPageBorder--) | Specificeert of de rand rond pagina's moet worden getoond. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Specificeert of de rand rond pagina's moet worden getoond. |
| [getShowFullScreen()](#getShowFullScreen--) | Toon/verberg volledige scherm-knop. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Toon/verberg volledige scherm-knop. |
| [getShowPageStepper()](#getShowPageStepper--) | Toon/verberg paginastepper. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Toon/verberg paginastepper. |
| [getShowSearch()](#getShowSearch--) | Toon/verberg zoeksectie. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Toon/verberg zoeksectie. |
| [getShowTopPane()](#getShowTopPane--) | Toon/verberg volledig bovenpaneel. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Toon/verberg volledig bovenpaneel. |
| [getShowBottomPane()](#getShowBottomPane--) | Toon/verberg onderpaneel. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Toon/verberg onderpaneel. |
| [getShowLeftPane()](#getShowLeftPane--) | Toon/verberg linkerpaneel. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Toon/verberg linkerpaneel. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Begin met geopend linkerpaneel. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Begin met geopend linkerpaneel. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Schakel contextmenu in/uit. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Schakel contextmenu in/uit. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Afbeelding die als logo in de rechterbovenhoek van de viewer wordt weergegeven. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Afbeelding die als logo in de rechterbovenhoek van de viewer wordt weergegeven. |
| [getLogoLink()](#getLogoLink--) | Haalt of stelt het volledige hyperlinkadres voor een logo in. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Haalt of stelt het volledige hyperlinkadres voor een logo in. |
| [getJpegQuality()](#getJpegQuality--) | Specificeert de kwaliteit van JPEG-afbeeldingen. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Specificeert de kwaliteit van JPEG-afbeeldingen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Standaardconstructor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Specificeert of het gegenereerde SWF-document moet worden gecomprimeerd of niet. Standaard is true.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Specificeert of het gegenereerde SWF-document moet worden gecomprimeerd of niet. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is true.

**Returns:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Specificeert of de rand rond pagina's moet worden getoond. Standaard is true.

**Returns:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Specificeert of de rand rond pagina's moet worden getoond. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Toon/verberg volledige scherm-knop. Kan worden overschreven in flashvars. Standaard is true.

**Returns:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Toon/verberg volledige scherm-knop. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true.

**Returns:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true.

**Returns:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Toon/verberg volledig bovenpaneel. Kan worden overschreven in flashvars. Standaard is true.

**Returns:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Toon/verberg volledig bovenpaneel. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Toon/verberg onderpaneel. Kan worden overschreven in flashvars. Standaard is true.

**Returns:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Toon/verberg onderpaneel. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Toon/verberg linkerpaneel. Kan worden overschreven in flashvars. Standaard is true.

**Returns:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Toon/verberg linkerpaneel. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Begin met geopend linkerpaneel. Kan worden overschreven in flashvars. Standaard is false.

**Returns:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Begin met geopend linkerpaneel. Kan worden overschreven in flashvars. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Schakel contextmenu in/uit. Standaard is true.

**Returns:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Schakel contextmenu in/uit. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Afbeelding die als logo in de rechterbovenhoek van de viewer wordt weergegeven. Afbeelding moet een PNG van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven.

**Returns:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Afbeelding die als logo in de rechterbovenhoek van de viewer wordt weergegeven. Afbeelding moet een PNG van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Haalt of stelt het volledige hyperlinkadres voor een logo in. Heeft alleen effect als een (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is gespecificeerd.

**Returns:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Haalt of stelt het volledige hyperlinkadres voor een logo in. Heeft alleen effect als een (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is gespecificeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Specificeert de kwaliteit van JPEG-afbeeldingen. Standaard is 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Specificeert de kwaliteit van JPEG-afbeeldingen. Standaard is 95.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Deze eigenschap ondersteunt het toewijzen van objecten van type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) niet.

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


**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Deze eigenschap ondersteunt het toewijzen van objecten van type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) niet.

--------------------

> ```
> Voorbeeld:
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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |