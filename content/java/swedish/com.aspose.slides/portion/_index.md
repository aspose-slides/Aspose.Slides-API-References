---
title: Portion
second_title: Aspose.Slides för Java API-referens
description: Representerar en del av text inuti ett textstycke.
type: docs
url: /sv/com.aspose.slides/portion/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Representerar en del av text inuti ett textstycke.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Portion()](#Portion--) | Initierar en ny instans av klassen Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Initierar en ny instans av klassen Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Initierar en ny instans av klassen Portion. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Returnerar formateringsobjekt som innehåller explicit angivna formateringsegenskaper för textdelen utan ärvd data. |
| [getText()](#getText--) | Hämtar eller anger enkeltexten för en del. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger enkeltexten för en del. |
| [getField()](#getField--) | Returnerar ett fält för den här delen. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konverterar den här delen till ett automatiskt uppdaterat fält. |
| [addField(String internalString)](#addField-java.lang.String-) | Konverterar den här delen till ett automatiskt uppdaterat fält. |
| [removeField()](#removeField--) | Konverterar detta fältavsnitt till en enkel del. |
| [getRect()](#getRect--) | Hämtar koordinaterna för rektangeln som omger delen. |
| [getCoordinates()](#getCoordinates--) | Hämtar koordinaterna för början av delen. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för en text. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för en text. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Initierar en ny instans av klassen Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Initierar en ny instans av klassen Portion.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Initierar en ny instans av klassen Portion.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Returnerar formateringsobjekt som innehåller explicit angivna formateringsegenskaper för textdelen utan ärvd data. Endast läsning [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Formateringsobjektet innehåller enbart formateringsparametrarna som definierats för den aktuella delen, ärvd data appliceras inte.

För att få de effektiva värdena inklusive ärvda, använd metoden [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Hämtar eller anger enkeltexten för en del. Läs/skriv String.

Värde: Texten.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Hämtar eller anger enkeltexten för en del. Läs/skriv String.

Värde: Texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Returnerar ett fält för den här delen. Endast läsning [IField](../../com.aspose.slides/ifield).

**Returnerar:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Konverterar den här delen till ett automatiskt uppdaterat fält.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Konverterar den här delen till ett automatiskt uppdaterat fält.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| internalString | java.lang.String | Internt namn för FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Konverterar detta fältavsnitt till en enkel del.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Hämtar koordinaterna för rektangeln som omger delen. Rektangeln inkluderar alla textrader i delen, även tomma.

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

**Returnerar:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Hämtar koordinaterna för början av delen. X-koordinaten representerar delens början från första tecknet inklusive vänster sidobäring. Y-koordinaten inkluderar översta sidobäringen.

**Returnerar:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för en text. Endast läsning [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för en text. Endast läsning [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Endast läsning IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject