---
title: HyperlinkManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Hyperlink-Verwaltung bereitstellen, Hinzufügen und Entfernen.
type: docs
url: /de/com.aspose.slides/hyperlinkmanager/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Verwaltung von Hyperlinks bereitstellen (Hinzufügen, Entfernen).

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Setzt externen Hyperlink beim Klicken. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Setzt internen Hyperlink beim Klicken. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Entfernt Hyperlink beim Klicken. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Setzt externen Hyperlink bei Mausüberfahrt. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Setzt internen Hyperlink bei Mausüberfahrt. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Entfernt Hyperlink bei Mausüberfahrt. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Setzt Makro-Hyperlink beim Klicken. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Setzt externen Hyperlink beim Klicken.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Instanziiert eine Presentation-Klasse, die ein PPTX darstellt
>  Presentation pres = new Presentation();
>  try {
>      // Holt die erste Folie in der Präsentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Fügt ein AutoShape-Objekt mit dem Typ Rechteck hinzu
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Castet die Form zu AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Greift auf die ITextFrame-Eigenschaft zu, die mit dem AutoShape verbunden ist
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Fügt dem Rahmen etwas Text hinzu
>      portion.setText("Aspose.Slides");
>      // Setzt den Hyperlink für den Textabschnitt
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Speichert die PPTX-Präsentation
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Rückgabewert:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Setzt internen Hyperlink beim Klicken.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Zielfolie. |

**Rückgabewert:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Entfernt Hyperlink beim Klicken.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Setzt externen Hyperlink bei Mausüberfahrt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Rückgabewert:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Setzt internen Hyperlink bei Mausüberfahrt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Zielfolie. |

**Rückgabewert:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Entfernt Hyperlink bei Mausüberfahrt.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Setzt Makro-Hyperlink beim Klicken.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| macroName | java.lang.String | Name des Makros |

**Rückgabewert:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink-Objekt [IHyperlink](../../com.aspose.slides/ihyperlink)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject