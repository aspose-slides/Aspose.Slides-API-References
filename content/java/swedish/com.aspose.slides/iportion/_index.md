---
title: IPortion
second_title: Aspose.Slides för Java API-referens
description: Representerar en del av texten i ett textstycke.
type: docs
url: /sv/com.aspose.slides/iportion/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Representerar en del av texten i ett textstycke.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Returnerar ett formateringsobjekt som innehåller explicit inställda formateringsegenskaper för textdelen utan att arv tillämpas. |
| [getText()](#getText--) | Hämtar eller anger den enkla texten för en del. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger den enkla texten för en del. |
| [getField()](#getField--) | Returnerar ett fält för denna del. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konverterar denna del till ett automatiskt uppdaterat fält. |
| [addField(String internalString)](#addField-java.lang.String-) | Konverterar denna del till ett automatiskt uppdaterat fält. |
| [removeField()](#removeField--) | Konverterar detta fältavsnitt till ett enkelt avsnitt. |
| [getRect()](#getRect--) | Hämta koordinaterna för rektangeln som omger delen. |
| [getCoordinates()](#getCoordinates--) | Hämta koordinaterna för början av delen. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Returnerar ett formateringsobjekt som innehåller explicit inställda formateringsegenskaper för textdelen utan att arv tillämpas. Skrivskyddad [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Formateringsobjektet innehåller endast formateringsparametrarna som definierats för den aktuella delen; ärvd data tillämpas inte.

För att få de effektiva värdena inklusive ärvda, använd metoden [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Hämtar eller anger den enkla texten för en del. Läs/skriv String.

Värde: Texten.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Hämtar eller anger den enkla texten för en del. Läs/skriv String.

Värde: Texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```


Returnerar ett fält för denna del. Skrivskyddad [IField](../../com.aspose.slides/ifield).

**Returnerar:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Konverterar denna del till ett automatiskt uppdaterat fält.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Typ av fält [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Konverterar denna del till ett automatiskt uppdaterat fält.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| internalString | java.lang.String | Internt namn för FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```


Konverterar detta fältavsnitt till ett enkelt avsnitt.

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Hämta koordinaterna för rektangeln som omger delen. Rektangeln inkluderar alla textrader i delen, inklusive tomma.

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
java.awt.geom.Rectangle2D.Float - Rektangel som omger delen java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```


Hämta koordinaterna för början av delen. X-koordinaten för punkten representerar delens början från det första tecknet inklusive vänster sidobäring. Y-koordinaten inkluderar övre sidobäring.

**Returnerar:**
java.awt.geom.Point2D.Float - Koordinaterna för början av delen java.awt.geom.Point2D.Float