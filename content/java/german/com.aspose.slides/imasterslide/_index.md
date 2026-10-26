---
title: IMasterSlide
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Masterfolie in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/imasterslide/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Stellt eine Masterfolie in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Masterfolie zurück. |
| [getTitleStyle()](#getTitleStyle--) | Gibt den Stil eines Titeltextes zurück. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Theme darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [getBodyStyle()](#getBodyStyle--) | Gibt den Stil eines Fließtextes zurück. |
| [getOtherStyle()](#getOtherStyle--) | Gibt den Stil eines anderen Textes zurück. |
| [getLayoutSlides()](#getLayoutSlides--) | Gibt die Sammlung von untergeordneten Layoutfolien für diese Masterfolie zurück. |
| [getPreserve()](#getPreserve--) | Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nachfolgenden Folien dieser Masterfolie gelöscht werden. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nachfolgenden Folien dieser Masterfolie gelöscht werden. |
| [hasDependingSlides()](#hasDependingSlides--) | Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. |
| [getDependingSlides()](#getDependingSlides--) | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Gibt den HeaderFooter-Manager der Masterfolie zurück. Nur-Lesen [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Rückgabe:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


Gibt den Stil eines Titeltextes zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Theme darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur externen Theme-Datei (.thmx). |

**Rückgabe:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Neuer thematisierter MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Gibt den Stil eines Fließtextes zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Gibt den Stil eines anderen Textes zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Gibt die Sammlung von untergeordneten Layoutfolien für diese Masterfolie zurück. Nur-Lesen [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Sie können über die Eigenschaft ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) auf die alternative API zum Hinzufügen/Einfgen/Entfernen/Klonen von Layoutfolien zugreifen.

**Rückgabe:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nachfolgenden Folien dieser Masterfolie gelöscht werden. Hinweis: Aspose.Slides entfernt niemals von selbst unbenutzte Masterfolien; um unbenutzte Masterfolien tatsächlich zu entfernen, rufen Sie [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) auf. Lese/Schreib boolesch.

**Rückgabe:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nachfolgenden Folien dieser Masterfolie gelöscht werden. Hinweis: Aspose.Slides entfernt niemals von selbst unbenutzte Masterfolien; um unbenutzte Masterfolien tatsächlich zu entfernen, rufen Sie [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) auf. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. Nur-Lesen boolesch.

**Rückgabe:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen.

**Rückgabe:**
com.aspose.slides.ISlide[] - Array von [ISlide](../../com.aspose.slides/islide), die von dieser Masterfolie abhängen
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. Nur-Lesen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Neuen vertikalen Zeichenleitfaden rechts von der Folienmitte hinzufügen
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)