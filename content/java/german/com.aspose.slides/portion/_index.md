---
title: Portion
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Textabschnitt innerhalb eines Textabsatzes dar.
type: docs
url: /de/com.aspose.slides/portion/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Stellt einen Textabschnitt innerhalb eines Textabsatzes dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Portion()](#Portion--) | Initialisiert eine neue Instanz der Klasse Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Initialisiert eine neue Instanz der Klasse Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Initialisiert eine neue Instanz der Klasse Portion. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Gibt ein Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wird. |
| [getText()](#getText--) | Liest oder setzt den Klartext eines Abschnitts. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Klartext eines Abschnitts. |
| [getField()](#getField--) | Gibt ein Feld dieses Abschnitts zurück. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld. |
| [addField(String internalString)](#addField-java.lang.String-) | Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld. |
| [removeField()](#removeField--) | Konvertiert diesen Feldabschnitt in einen einfachen Abschnitt. |
| [getRect()](#getRect--) | Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. |
| [getCoordinates()](#getCoordinates--) | Ermittelt die Koordinaten des Beginns des Abschnitts. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie des Textes zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation des Textes zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Initialisiert eine neue Instanz der Klasse Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Initialisiert eine neue Instanz der Klasse Portion.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Initialisiert eine neue Instanz der Klasse Portion.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Gibt ein Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wird. Nur lesbar [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Das Formatierungsobjekt enthält nur die für den aktuellen Abschnitt definierten Formatierungsparameter; vererbte Daten werden nicht angewendet.

Um die effektiven Werte einschließlich der vererbten zu erhalten, verwenden Sie die Methode [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Liest oder setzt den Klartext eines Abschnitts. Lesen/Schreiben String.

Wert: Der Text.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Liest oder setzt den Klartext eines Abschnitts. Lesen/Schreiben String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Gibt ein Feld dieses Abschnitts zurück. Nur lesbar [IField](../../com.aspose.slides/ifield).

**Rückgabe:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| internalString | java.lang.String | Interner Name von FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Konvertiert diesen Feldabschnitt in einen einfachen Abschnitt.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. Das Rechteck umfasst alle Textzeilen im Abschnitt, einschließlich leerer.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Ermittelt die Koordinaten des Beginns des Abschnitts. Die X-Koordinate des Punktes stellt den Beginn des Abschnitts ab dem ersten Zeichen einschließlich des linken Seitenrands dar. Die Y-Koordinate beinhaltet den oberen Seitenrand.

**Rückgabe:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines Textes zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines Textes zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Objekt Parent_Immediate zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject