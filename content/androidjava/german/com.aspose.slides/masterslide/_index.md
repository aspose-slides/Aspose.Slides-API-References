---
title: MasterSlide
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getTitleStyle()](#getTitleStyle--) | Gibt den Stil eines Titeltextes zurück. |
| [getBodyStyle()](#getBodyStyle--) | Gibt den Stil eines Textkörpers zurück. |
| [getOtherStyle()](#getOtherStyle--) | Gibt den Stil eines anderen Textes zurück. |
| [getLayoutSlides()](#getLayoutSlides--) | Gibt die Sammlung von untergeordneten Layoutfolien für diese Masterfolie zurück. |
| [getPreserve()](#getPreserve--) | Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle Folien, die dieser Masterfolie folgen, gelöscht werden. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle Folien, die dieser Masterfolie folgen, gelöscht werden. |
| [getDependingSlides()](#getDependingSlides--) | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| [hasDependingSlides()](#hasDependingSlides--) | Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. |
| [getThemeManager()](#getThemeManager--) | Gibt den Theme-Manager zurück. |
| [getName()](#getName--) | Gibt den Namen einer Masterfolie zurück oder setzt ihn. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Masterfolie zurück oder setzt ihn. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenführungen für die Masterfolie zurück. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Masterfolie zurück. Nur-Lesen [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

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
[IMasterSlide](../../com.aspose.slides/imasterslide) - Neue thematisierte MasterSlide.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Gibt den Stil eines Titeltextes zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Gibt den Stil eines Textkörpers zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Gibt den Stil eines anderen Textes zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Gibt die Sammlung von untergeordneten Layoutfolien für diese Masterfolie zurück. Nur-Lesen [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Sie können über die Eigenschaft ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) auf alternative APIs zum Hinzufügen/Einfügen/Entfernen/Klonen von Layoutfolien zugreifen.

**Rückgabe:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle Folien, die dieser Masterfolie folgen, gelöscht werden. Hinweis: Aspose.Slides entfernt niemals eine nicht verwendete Masterfolie von selbst; um nicht verwendete Masterfolien tatsächlich zu entfernen, rufen Sie [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) auf. Lesen/Schreiben  boolean .

**Rückgabe:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle Folien, die dieser Masterfolie folgen, gelöscht werden. Hinweis: Aspose.Slides entfernt niemals eine nicht verwendete Masterfolie von selbst; um nicht verwendete Masterfolien tatsächlich zu entfernen, rufen Sie [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) auf. Lesen/Schreiben  boolean .

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
com.aspose.slides.ISlide[] - Array von [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. Nur-Lesen  boolean .

**Rückgabe:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Gibt den Theme-Manager zurück. Nur-Lesen [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Rückgabe:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Gibt den Namen einer Masterfolie zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Gibt den Namen einer Masterfolie zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lesen/Schreiben  boolean .

**Rückgabe:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Gibt eine Sammlung von Zeichenführungen für die Masterfolie zurück. Nur-Lesen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Fügt die neue vertikale Zeichenführung rechts von der Folienmitte hinzu
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)