---
title: IPortion
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Teil eines Textes innerhalb eines Textabsatzes dar.
type: docs
url: /de/com.aspose.slides/iportion/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Stellt einen Teil eines Textes innerhalb eines Textabsatzes dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Gibt ein Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textteils enthält, ohne dass Vererbung angewendet wird. |
| [getText()](#getText--) | Liest oder setzt den einfachen Text eines Teils. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den einfachen Text eines Teils. |
| [getField()](#getField--) | Gibt ein Feld dieses Teils zurück. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konvertiert diesen Teil in das automatisch aktualisierte Feld. |
| [addField(String internalString)](#addField-java.lang.String-) | Konvertiert diesen Teil in das automatisch aktualisierte Feld. |
| [removeField()](#removeField--) | Konvertiert diesen Feldteil in den einfachen Teil. |
| [getRect()](#getRect--) | Ermittelt die Koordinaten des Rechtecks, das den Teil begrenzt. |
| [getCoordinates()](#getCoordinates--) | Ermittelt die Koordinaten des Beginns des Teils. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Gibt ein Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textteils enthält, ohne dass Vererbung angewendet wird. Nur lesbar [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Das Formatierungsobjekt enthält nur die für den aktuellen Teil definierten Formatierungsparameter; vererbte Daten werden nicht angewendet.

Um die wirksamen Werte einschließlich vererbter zu erhalten, verwenden Sie die Methode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Liest oder setzt den einfachen Text eines Teils. Lesen/Schreiben String.

Wert: Der Text.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Liest oder setzt den einfachen Text eines Teils. Lesen/Schreiben String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```


Gibt ein Feld dieses Teils zurück. Nur lesbar [IField](../../com.aspose.slides/ifield).

**Rückgabe:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Konvertiert diesen Teil in das automatisch aktualisierte Feld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Typ des Feldes [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Konvertiert diesen Teil in das automatisch aktualisierte Feld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| internalString | java.lang.String | Interner Name des FieldTypeEx-Strings |
### removeField() {#removeField--}
```
public abstract void removeField()
```


Konvertiert diesen Feldteil in den einfachen Teil.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Ermittelt die Koordinaten des Rechtecks, das den Teil begrenzt. Das Rechteck umfasst alle Textzeilen im Teil, einschließlich leerer Zeilen.

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
java.awt.geom.Rectangle2D.Float - Rechteck, das den Teil begrenzt java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```


Ermittelt die Koordinaten des Beginns des Teils. Die X-Koordinate des Punktes gibt den Beginn des Teils ab dem ersten Zeichen einschließlich des linken Seitenabstandes an. Die Y-Koordinate enthält den oberen Seitenabstand.

**Rückgabe:**
java.awt.geom.Point2D.Float - Koordinaten des Beginns des Teils java.awt.geom.Point2D.Float