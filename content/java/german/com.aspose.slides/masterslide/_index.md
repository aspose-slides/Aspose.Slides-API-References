---
title: MasterSlide
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Masterfolie in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/masterslide/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Stellt eine Masterfolie in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Masterfolie zurück. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Theme darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [getTitleStyle()](#getTitleStyle--) | Gibt den Stil eines Titeltexts zurück. |
| [getBodyStyle()](#getBodyStyle--) | Gibt den Stil eines Fließtextes zurück. |
| [getOtherStyle()](#getOtherStyle--) | Gibt den Stil eines weiteren Textes zurück. |
| [getLayoutSlides()](#getLayoutSlides--) | Gibt die Sammlung von untergeordneten Layoutfolien für diese Masterfolie zurück. |
| [getPreserve()](#getPreserve--) | Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nach ihr folgenden Folien gelöscht werden. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nach ihr folgenden Folien gelöscht werden. |
| [getDependingSlides()](#getDependingSlides--) | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| [hasDependingSlides()](#hasDependingSlides--) | Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. |
| [getThemeManager()](#getThemeManager--) | Gibt den Theme-Manager zurück. |
| [getName()](#getName--) | Gibt den Namen einer Masterfolie zurück oder legt ihn fest. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Masterfolie zurück oder legt ihn fest. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Masterfolie zurück. Nur lesend [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Rückgabe:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Theme darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur externen Theme-Datei (.thmx). |

**Rückgabe:**
[IMasterSlide](../../com.aspose.slides/imasterslide) – Neue thematisierte MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Gibt den Stil eines Titeltexts zurück. Nur lesend [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Gibt den Stil eines Fließtextes zurück. Nur lesend [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Gibt den Stil eines weiteren Textes zurück. Nur lesend [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Gibt die Sammlung von untergeordneten Layoutfolien für diese Masterfolie zurück. Nur lesend [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Sie können auf die alternative API zum Hinzufügen/Einfügen/Entfernen/Klonen von Layoutfolien über die Eigenschaft ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) zugreifen.

**Rückgabe:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nach ihr folgenden Folien gelöscht werden. Hinweis: Aspose.Slides entfernt niemals automatisch ungenutzte Masterfolien; um ungenutzte Masterfolien tatsächlich zu entfernen, rufen Sie [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lesen/Schreiben  boolean  auf.

**Rückgabe:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle nach ihr folgenden Folien gelöscht werden. Hinweis: Aspose.Slides entfernt niemals automatisch ungenutzte Masterfolien; um ungenutzte Masterfolien tatsächlich zu entfernen, rufen Sie [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lesen/Schreiben  boolean  auf.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen.

**Rückgabe:**
com.aspose.slides.ISlide[] – Array von [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. Nur lesend  boolean .

**Rückgabe:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Gibt den Theme-Manager zurück. Nur lesend [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Rückgabe:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Gibt den Namen einer Masterfolie zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Gibt den Namen einer Masterfolie zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst liefert diese Eigenschaft immer  false . Lesen/Schreiben  boolean .

**Rückgabe:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst liefert diese Eigenschaft immer  false . Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. Nur lesend [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Hinzufügen des neuen vertikalen Zeichenleitfadens rechts von der Folienmitte
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)