---
title: SwfOptions
second_title: Aspose.Slides pro Android přes Java API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Swf.
type: docs
url: /cs/com.aspose.slides/swfoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechny implementované rozhraní:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Ukládání prezentace a stránek poznámek
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Výchozí konstruktor. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getCompressed()](#getCompressed--) | Určuje, zda má být vygenerovaný SWF dokument komprimován, nebo ne. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Určuje, zda má být vygenerovaný SWF dokument komprimován, nebo ne. |
| [getViewerIncluded()](#getViewerIncluded--) | Určuje, zda má vygenerovaný SWF dokument zahrnovat integrovaný prohlížeč dokumentů, nebo ne. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Určuje, zda má vygenerovaný SWF dokument zahrnovat integrovaný prohlížeč dokumentů, nebo ne. |
| [getShowPageBorder()](#getShowPageBorder--) | Určuje, zda má být zobrazen okraj kolem stránek. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Určuje, zda má být zobrazen okraj kolem stránek. |
| [getShowFullScreen()](#getShowFullScreen--) | Zobrazit/skrýt tlačítko celé obrazovky. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Zobrazit/skrýt tlačítko celé obrazovky. |
| [getShowPageStepper()](#getShowPageStepper--) | Zobrazit/skrýt krokovač stránek. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Zobrazit/skrýt krokovač stránek. |
| [getShowSearch()](#getShowSearch--) | Zobrazit/skrýt sekci hledání. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Zobrazit/skrýt sekci hledání. |
| [getShowTopPane()](#getShowTopPane--) | Zobrazit/skrýt celý horní panel. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Zobrazit/skrýt celý horní panel. |
| [getShowBottomPane()](#getShowBottomPane--) | Zobrazit/skrýt spodní panel. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Zobrazit/skrýt spodní panel. |
| [getShowLeftPane()](#getShowLeftPane--) | Zobrazit/skrýt levý panel. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Zobrazit/skrýt levý panel. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Spustit s otevřeným levým panelem. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Spustit s otevřeným levým panelem. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Povolit/zakázat kontextové menu. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Povolit/zakázat kontextové menu. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. |
| [getLogoLink()](#getLogoLink--) | Získá nebo nastaví úplnou hypertextovou adresu pro logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Získá nebo nastaví úplnou hypertextovou adresu pro logo. |
| [getJpegQuality()](#getJpegQuality--) | Určuje kvalitu JPEG obrázků. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Určuje kvalitu JPEG obrázků. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Výchozí konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Návratová hodnota:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Určuje, zda má být vygenerovaný SWF dokument komprimován, nebo ne. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Určuje, zda má být vygenerovaný SWF dokument komprimován, nebo ne. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Určuje, zda má vygenerovaný SWF dokument zahrnovat integrovaný prohlížeč dokumentů, nebo ne. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Určuje, zda má vygenerovaný SWF dokument zahrnovat integrovaný prohlížeč dokumentů, nebo ne. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Určuje, zda má být zobrazen okraj kolem stránek. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Určuje, zda má být zobrazen okraj kolem stránek. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Zobrazit/skrýt tlačítko celé obrazovky. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Zobrazit/skrýt tlačítko celé obrazovky. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Zobrazit/skrýt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Zobrazit/skrýt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Zobrazit/skrýt sekci hledání. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Zobrazit/skrýt sekci hledání. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Zobrazit/skrýt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Zobrazit/skrýt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Zobrazit/skrýt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Zobrazit/skrýt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Zobrazit/skrýt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Zobrazit/skrýt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Spustit s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false.

**Návratová hodnota:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Spustit s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Povolit/zakázat kontextové menu. Výchozí hodnota je true.

**Návratová hodnota:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Povolit/zakázat kontextové menu. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl být PNG o rozměrech 32x64 pixelů, jinak může být logo zobrazováno nesprávně.

**Návratová hodnota:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl být PNG o rozměrech 32x64 pixelů, jinak může být logo zobrazováno nesprávně.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Získá nebo nastaví úplnou hypertextovou adresu pro logo. Má účinek jen pokud je specifikováno (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Návratová hodnota:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Získá nebo nastaví úplnou hypertextovou adresu pro logo. Má účinek jen pokud je specifikováno (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Určuje kvalitu JPEG obrázků. Výchozí hodnota je 95.

**Návratová hodnota:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Určuje kvalitu JPEG obrázku. Výchozí hodnota je 95.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Toto vlastnost nepodporuje přiřazení objektů typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

**Návratová hodnota:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Toto vlastnost nepodporuje přiřazení objektů typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |