---
title: ISwfOptions
second_title: Aspose.Slides pro Android prostřednictvím Java API reference
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
| [getCompressed()](#getCompressed--) | Určuje, zda má být generovaný SWF dokument komprimován, nebo ne. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Určuje, zda má být generovaný SWF dokument komprimován, nebo ne. |
| [getViewerIncluded()](#getViewerIncluded--) | Určuje, zda má být generovaný SWF dokument zahrnout integrovaný prohlížeč dokumentu, nebo ne. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Určuje, zda má být generovaný SWF dokument zahrnout integrovaný prohlížeč dokumentu, nebo ne. |
| [getShowPageBorder()](#getShowPageBorder--) | Určuje, zda má být okraj kolem stránek zobrazen. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Určuje, zda má být okraj kolem stránek zobrazen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má být vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má být vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getShowFullScreen()](#getShowFullScreen--) | Zobrazit/skrýt tlačítko celé obrazovky. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Zobrazit/skrýt tlačítko celé obrazovky. |
| [getShowPageStepper()](#getShowPageStepper--) | Zobrazit/skrýt krokovač stránek. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Zobrazit/skrýt krokovač stránek. |
| [getShowSearch()](#getShowSearch--) | Zobrazit/skrýt sekci vyhledávání. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Zobrazit/skrýt sekci vyhledávání. |
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
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získá nebo nastaví režim, v němž jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získá nebo nastaví režim, v němž jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Určuje, zda má být generovaný SWF dokument komprimován, nebo ne. Výchozí hodnota je true.

**Vrací:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Určuje, zda má být generovaný SWF dokument komprimován, nebo ne. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Určuje, zda má být generovaný SWF dokument zahrnout integrovaný prohlížeč dokumentu, nebo ne. Výchozí hodnota je true.

**Vrací:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Určuje, zda má být generovaný SWF dokument zahrnout integrovaný prohlížeč dokumentu, nebo ne. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Určuje, zda má být okraj kolem stránek zobrazen. Výchozí hodnota je true.

**Vrací:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Určuje, zda má být okraj kolem stránek zobrazen. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Určuje, zda má být vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Určuje, zda má být vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Zobrazit/skrýt tlačítko celé obrazovky. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Zobrazit/skrýt tlačítko celé obrazovky. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Zobrazit/skrýt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Zobrazit/skrýt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Zobrazit/skrýt sekci vyhledávání. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Zobrazit/skrýt sekci vyhledávání. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Zobrazit/skrýt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Zobrazit/skrýt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Zobrazit/skrýt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Zobrazit/skrýt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Zobrazit/skrýt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Vrací:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Zobrazit/skrýt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Spustit s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false.

**Vrací:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Spustit s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Povolit/zakázat kontextové menu. Výchozí hodnota je true.

**Vrací:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Povolit/zakázat kontextové menu. Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl být PNG o rozměrech 32 x 64 pixelů, jinak může logo být zobrazeno nesprávně.

**Vrací:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl být PNG o rozměrech 32 x 64 pixelů, jinak může logo být zobrazeno nesprávně.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Získá nebo nastaví úplnou hypertextovou adresu pro logo. Má vliv jen pokud je specifikováno (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Vrací:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Získá nebo nastaví úplnou hypertextovou adresu pro logo. Má vliv jen pokud je specifikováno (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

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

Získá nebo nastaví režim, v němž jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Tato vlastnost nepodporuje přiřazování objektů typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

Získá nebo nastaví režim, v němž jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Tato vlastnost nepodporuje přiřazování objektů typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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