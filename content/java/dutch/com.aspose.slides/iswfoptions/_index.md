---
title: ISwfOptions
second_title: Aspose.Slides voor Java API Referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in SWF-formaat.
type: docs
url: /nl/com.aspose.slides/iswfoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in SWF-formaat.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCompressed()](#getCompressed--) | Geeft aan of het gegenereerde SWF-document al dan niet moet worden gecomprimeerd. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Geeft aan of het gegenereerde SWF-document al dan niet moet worden gecomprimeerd. |
| [getViewerIncluded()](#getViewerIncluded--) | Geeft aan of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Geeft aan of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. |
| [getShowPageBorder()](#getShowPageBorder--) | Geeft aan of de rand rond pagina’s moet worden getoond. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Geeft aan of de rand rond pagina’s moet worden getoond. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Geeft aan of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Geeft aan of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [getShowFullScreen()](#getShowFullScreen--) | Toon/verberg volledigschermknop. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Toon/verberg volledigschermknop. |
| [getShowPageStepper()](#getShowPageStepper--) | Toon/verberg paginastapregel. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Toon/verberg paginastapregel. |
| [getShowSearch()](#getShowSearch--) | Toon/verberg zoeksectie. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Toon/verberg zoeksectie. |
| [getShowTopPane()](#getShowTopPane--) | Toon/verberg volledige bovenste paneel. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Toon/verberg volledige bovenste paneel. |
| [getShowBottomPane()](#getShowBottomPane--) | Toon/verberg onderste paneel. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Toon/verberg onderste paneel. |
| [getShowLeftPane()](#getShowLeftPane--) | Toon/verberg linker paneel. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Toon/verberg linker paneel. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Begin met geopende linker paneel. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Begin met geopende linker paneel. |
| [getEnableContextMenu()](#getEnableContextMenu--) | In- of uitschakelen contextmenu. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | In- of uitschakelen contextmenu. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Afbeelding die als logo in de rechterbovenhoek van de viewer wordt getoond. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Afbeelding die als logo in de rechterbovenhoek van de viewer wordt getoond. |
| [getLogoLink()](#getLogoLink--) | Haalt of stelt het volledige hyperlink-adres voor een logo in. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Haalt of stelt het volledige hyperlink-adres voor een logo in. |
| [getJpegQuality()](#getJpegQuality--) | Geeft de kwaliteit van JPEG-afbeeldingen op. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Geeft de kwaliteit van JPEG-afbeeldingen op. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Geeft aan of het gegenereerde SWF-document al dan niet moet worden gecomprimeerd. Standaard is true.

**Retour:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Geeft aan of het gegenereerde SWF-document al dan niet moet worden gecomprimeerd. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Geeft aan of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is true.

**Retour:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Geeft aan of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Geeft aan of de rand rond pagina’s moet worden getoond. Standaard is true.

**Retour:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Geeft aan of de rand rond pagina’s moet worden getoond. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Geeft aan of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

**Retour:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Geeft aan of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Toon/verberg volledigschermknop. Kan worden overschreven in flashvars. Standaard is true.

**Retour:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Toon/verberg volledigschermknop. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Toon/verberg paginastapregel. Kan worden overschreven in flashvars. Standaard is true.

**Retour:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Toon/verberg paginastapregel. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true.

**Retour:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Toon/verberg volledige bovenste paneel. Kan worden overschreven in flashvars. Standaard is true.

**Retour:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Toon/verberg volledige bovenste paneel. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Toon/verberg onderste paneel. Kan worden overschreven in flashvars. Standaard is true.

**Retour:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Toon/verberg onderste paneel. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Toon/verberg linker paneel. Kan worden overschreven in flashvars. Standaard is true.

**Retour:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Toon/verberg linker paneel. Kan worden overschreven in flashvars. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Begin met geopende linker paneel. Kan worden overschreven in flashvars. Standaard is false.

**Retour:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Begin met geopende linker paneel. Kan worden overschreven in flashvars. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

In- of uitschakelen contextmenu. Standaard is true.

**Retour:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

In- of uitschakelen contextmenu. Standaard is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Afbeelding die als logo in de rechterbovenhoek van de viewer wordt getoond. Afbeelding dient een PNG-bestand van 32 × 64 pixels te zijn, anders kan het logo onjuist worden weergegeven.

**Retour:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Afbeelding die als logo in de rechterbovenhoek van de viewer wordt getoond. Afbeelding dient een PNG-bestand van 32 × 64 pixels te zijn, anders kan het logo onjuist worden weergegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Haalt of stelt het volledige hyperlink-adres voor een logo in. Heeft alleen effect als een (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is gespecificeerd.

**Retour:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Haalt of stelt het volledige hyperlink-adres voor een logo in. Heeft alleen effect als een (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is gespecificeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Geeft de kwaliteit van JPEG-afbeeldingen op. Standaard is 95.

**Retour:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Geeft de kwaliteit van JPEG-afbeeldingen op. Standaard is 95.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Haalt of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Deze eigenschap ondersteunt geen toewijzing van objecten van type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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


**Retour:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Haalt of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Deze eigenschap ondersteunt geen toewijzing van objecten van type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |