---
title: XpsOptions
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu XPS.
type: docs
url: /cs/com.aspose.slides/xpsoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechny implementované rozhraní:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Ukládání prezentace do XPS dokumentu
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Vytvořte instanci třídy TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Uložit MetaFiles jako PNG
>      options.setSaveMetafilesAsPng(true);
>      // Uložit prezentaci do XPS dokumentu
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Výchozí konstruktor. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda vygenerovaný dokument má obsahovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda vygenerovaný dokument má obsahovat skryté snímky, nebo ne. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True k převodu všech metafiles použitých v prezentaci na PNG obrázky. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True k převodu všech metafiles použitých v prezentaci na PNG obrázky. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True k vykreslení černého rámečku kolem každého snímku. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True k vykreslení černého rámečku kolem každého snímku. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Výchozí konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Určuje, zda vygenerovaný dokument má obsahovat skryté snímky, nebo ne. Výchozí hodnota je **false**.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Určuje, zda vygenerovaný dokument má obsahovat skryté snímky, nebo ne. Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


True k převodu všech metafiles použitých v prezentaci na PNG obrázky. Boolean s možností čtení i zápisu.

--------------------

Výchozí hodnota je **true**.

**Vrací:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


True k převodu všech metafiles použitých v prezentaci na PNG obrázky. Boolean s možností čtení i zápisu.

--------------------

Výchozí hodnota je **true**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


True k vykreslení černého rámečku kolem každého snímku. Boolean s možností čtení i zápisu.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


True k vykreslení černého rámečku kolem každého snímku. Boolean s možností čtení i zápisu.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |