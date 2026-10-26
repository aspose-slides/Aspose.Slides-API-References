---
title: IPortion
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt einen Textabschnitt innerhalb eines Textabsatzes dar.
type: docs
url: /de/com.aspose.slides/iportion/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Stellt einen Textabschnitt innerhalb eines Textabsatzes dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Gibt ein Formatierungsobjekt zurück, das explizit festgelegte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wird. |
| [getText()](#getText--) | Liest oder setzt den Klartext eines Abschnitts. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Klartext eines Abschnitts. |
| [getField()](#getField--) | Gibt ein Feld dieses Abschnitts zurück. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld. |
| [addField(String internalString)](#addField-java.lang.String-) | Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld. |
| [removeField()](#removeField--) | Konvertiert diesen Feldabschnitt in den einfachen Abschnitt. |
| [getRect()](#getRect--) | Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. |
| [getCoordinates()](#getCoordinates--) | Ermittelt die Koordinaten des Anfangs des Abschnitts. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Gibt ein Formatierungsobjekt zurück, das explizit festgelegte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wird. Nur lesbar [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Das Formatierungsobjekt enthält nur die für den aktuellen Abschnitt definierten Formatierungsparameter; vererbte Daten werden nicht angewendet.

Um die effektiven Werte einschließlich der geerbten zu erhalten, verwenden Sie die Methode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Liest oder setzt den Klartext eines Abschnitts. Lese/Schreib String.

Wert: Der Text.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Liest oder setzt den Klartext eines Abschnitts. Lese/Schreib String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```


Gibt ein Feld dieses Abschnitts zurück. Nur lesbar [IField](../../com.aspose.slides/ifield).

**Rückgabe:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Typ des Feldes [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Konvertiert diesen Abschnitt in ein automatisch aktualisiertes Feld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| internalString | java.lang.String | Interner Name von FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```


Konvertiert diesen Feldabschnitt in den einfachen Abschnitt.

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. Das Rechteck umfasst alle Textzeilen im Abschnitt, einschließlich leerer Zeilen.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
android.graphics.RectF - Rechteck, das den Abschnitt begrenzt android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```


Ermittelt die Koordinaten des Anfangs des Abschnitts. Die X-Koordinate des Punktes stellt den Beginn des Abschnitts vom ersten Zeichen einschließlich des linken Seitenrandes dar. Die Y-Koordinate beinhaltet den oberen Seitenrand.

**Rückgabe:**
android.graphics.PointF - Koordinaten des Anfangs des Abschnitts android.graphics.PointF