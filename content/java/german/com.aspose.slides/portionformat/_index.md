---
title: PortionFormat
second_title: Aspose.Slides für Java API-Referenz
description: Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts.
type: docs
url: /de/com.aspose.slides/portionformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Instanziiert ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides verwendet diese speziellen Bezeichner (ähnlich denen, die in PowerPoint verwendet werden):
>      // +mn-lt - Körperschrift Latein (Kleinere lateinische Schrift)
>      // +mj-lt - Überschriftschrift Latein (Hauptlateinische Schrift)
>      // +mn-ea - Körperschrift Ostasiatisch (Kleinere ostasiatische Schrift)
>      // +mj-ea - Körperschrift Ostasiatisch (Kleinere ostasiatische Schrift)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte inklusive Vererbung zu erhalten, müssen Sie die Methode [getEffective](../../com.aspose.slides/portionformat\#getEffective) verwenden, die eine [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-Instanz zurückgibt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Initialisiert eine neue Instanz der Klasse [PortionFormat](../../com.aspose.slides/portionformat). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Gibt die Bookmark-ID zurück oder legt sie fest. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Gibt die Bookmark-ID zurück oder legt sie fest. |
| [getSmartTagClean()](#getSmartTagClean--) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Gibt den für ein Mouse-Over definierten Hyperlink zurück oder legt ihn fest. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Gibt den für ein Mouse-Over definierten Hyperlink zurück oder legt ihn fest. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Hyperlink-Manager. |
| [getEffective()](#getEffective--) | Liefert die effektiven Formatierungsdaten des Abschnitts mit angewendeter Vererbung. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Initialisiert eine neue Instanz der Klasse [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Gibt die Bookmark-ID zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Gibt die Bookmark-ID zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabewert:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Gibt den für ein Mouse-Over definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabewert:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Gibt den für ein Mouse-Over definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Hyperlink-Manager. Nur-Lesen [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Rückgabewert:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Liefert die effektiven Formatierungsdaten des Abschnitts mit angewendeter Vererbung.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).