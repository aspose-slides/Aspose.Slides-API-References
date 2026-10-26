---
title: ISwfOptions
second_title: Aspose.Slides pro Java – referenční příručka API
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu SWF.
type: docs
url: /cs/com.aspose.slides/iswfoptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu SWF.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCompressed()](#getCompressed--) | Určuje, zda má být generovaný dokument SWF komprimován, nebo ne. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Určuje, zda má být generovaný dokument SWF komprimován, nebo ne. |
| [getViewerIncluded()](#getViewerIncluded--) | Určuje, zda má být generovaný dokument SWF vybaven integrovaným prohlížečem dokumentů, nebo ne. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Určuje, zda má být generovaný dokument SWF vybaven integrovaným prohlížečem dokumentů, nebo ne. |
| [getShowPageBorder()](#getShowPageBorder--) | Určuje, zda má být kolem stránek zobrazena ohraničující rámeček. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Určuje, zda má být kolem stránek zobrazena ohraničující rámeček. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má být generovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má být generovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getShowFullScreen()](#getShowFullScreen--) | Zobrazí/skrývá tlačítko na celou obrazovku. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Zobrazí/skrývá tlačítko na celou obrazovku. |
| [getShowPageStepper()](#getShowPageStepper--) | Zobrazí/skrývá ovladač krokování stránky. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Zobrazí/skrývá ovladač krokování stránky. |
| [getShowSearch()](#getShowSearch--) | Zobrazí/skrývá sekci vyhledávání. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Zobrazí/skrývá sekci vyhledávání. |
| [getShowTopPane()](#getShowTopPane--) | Zobrazí/skrývá celý horní panel. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Zobrazí/skrývá celý horní panel. |
| [getShowBottomPane()](#getShowBottomPane--) | Zobrazí/skrývá spodní panel. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Zobrazí/skrývá spodní panel. |
| [getShowLeftPane()](#getShowLeftPane--) | Zobrazí/skrývá levý panel. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Zobrazí/skrývá levý panel. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Spustí s otevřeným levým panelem. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Spustí s otevřeným levým panelem. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Povolí/zakáže kontextovou nabídku. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Povolí/zakáže kontextovou nabídku. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. |
| [getLogoLink()](#getLogoLink--) | Získává nebo nastavuje úplnou hypertextovou adresu pro logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Získává nebo nastavuje úplnou hypertextovou adresu pro logo. |
| [getJpegQuality()](#getJpegQuality--) | Určuje kvalitu JPEG obrázků. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Určuje kvalitu JPEG obrázků. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Určuje, zda má být generovaný dokument SWF komprimován, nebo ne. Výchozí hodnota je true.

**Vrací:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Určuje, zda má být generovaný dokument SWF komprimován, nebo ne. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Určuje, zda má být generovaný dokument SWF vybaven integrovaným prohlížečem dokumentů, nebo ne. Výchozí hodnota je true.

**Vrací:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Určuje, zda má být generovaný dokument SWF vybaven integrovaným prohlížečem dokumentů, nebo ne. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Určuje, zda má být kolem stránek zobrazena ohraničující rámeček. Výchozí hodnota je true.

**Vrací:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Určuje, zda má být kolem stránek zobrazena ohraničující rámeček. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Určuje, zda má být generovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Určuje, zda má být generovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Zobrazí/skrývá tlačítko na celou obrazovku. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Zobrazí/skrývá tlačítko na celou obrazovku. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Zobrazí/skrývá ovladač krokování stránky. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Zobrazí/skrývá ovladač krokování stránky. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Zobrazí/skrývá sekci vyhledávání. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Zobrazí/skrývá sekci vyhledávání. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Zobrazí/skrývá celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Zobrazí/skrývá celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Zobrazí/skrývá spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Zobrazí/skrývá spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Zobrazí/skrývá levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Zobrazí/skrývá levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Spustí s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false.

**Vrací:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Spustí s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Povolí/zakáže kontextovou nabídku. Výchozí hodnota je true.

**Vrací:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Povolí/zakáže kontextovou nabídku. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl mít rozměry 32 × 64 pixelů ve formátu PNG, jinak může být logo zobrazeno nesprávně.

**Vrací:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl mít rozměry 32 × 64 pixelů ve formátu PNG, jinak může být logo zobrazeno nesprávně.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Získává nebo nastavuje úplnou hypertextovou adresu pro logo. Má efekt pouze pokud je zadáno (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Vrací:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Získává nebo nastavuje úplnou hypertextovou adresu pro logo. Má efekt pouze pokud je zadáno (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Určuje kvalitu JPEG obrázků. Výchozí hodnota je 95.

**Vrací:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Určuje kvalitu JPEG obrázků. Výchozí hodnota je 95.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Tato vlastnost nepodporuje přiřazení objektů typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

**Vrací:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Tato vlastnost nepodporuje přiřazení objektů typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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