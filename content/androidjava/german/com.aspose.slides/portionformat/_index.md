---
title: PortionFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
>  //Instanziieren Sie ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides verwendet diese speziellen Bezeichner (ähnlich denen, die in PowerPoint verwendet werden):
>      // +mn-lt - Körper-Schriftart Latein (Minor Latin Font)
>      // +mj-lt - Überschrift-Schriftart Latein (Major Latin Font)
>      // +mn-ea - Körper-Schriftart Ostasiatisch (Minor East Asian Font)
>      // +mj-ea - Körper-Schriftart Ostasiatisch (Minor East Asian Font)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [getEffective](../../com.aspose.slides/portionformat\#getEffective) verwenden, die eine [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-Instanz zurückgibt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Initialisiert eine neue Instanz der [PortionFormat](../../com.aspose.slides/portionformat) Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Gibt den Bookmark-Bezeichner zurück oder setzt ihn. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Gibt den Bookmark-Bezeichner zurück oder setzt ihn. |
| [getSmartTagClean()](#getSmartTagClean--) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Gibt den für Mouse-Over definierten Hyperlink zurück oder setzt ihn. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Gibt den für Mouse-Over definierten Hyperlink zurück oder setzt ihn. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Hyperlink-Manager. |
| [getEffective()](#getEffective--) | Ermittelt die effektiven Formatierungsdaten des Abschnitts mit angewendeter Vererbung. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Initialisiert eine neue Instanz der [PortionFormat](../../com.aspose.slides/portionformat) Klasse.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Gibt den Bookmark-Bezeichner zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Gibt den Bookmark-Bezeichner zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen/Schreiben boolean.

**Rückgabe:**
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

Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Gibt den für Mouse-Over definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Gibt den für Mouse-Over definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Hyperlink-Manager. Nur-Lesen [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Rückgabe:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Ermittelt die effektiven Formatierungsdaten des Abschnitts mit angewendeter Vererbung.

--------------------

> ```
> Dieses Beispiel demonstriert das Abrufen einiger effektiver Abschnittsformat-Eigenschaften.
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


**Rückgabe:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).