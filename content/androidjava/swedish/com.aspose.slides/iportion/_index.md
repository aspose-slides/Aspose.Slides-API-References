---
title: IPortion
second_title: Aspose.Slides för Android via Java API-referens
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
| [getPortionFormat()](#getPortionFormat--) | Returnerar ett formateringsobjekt som innehåller explicit angivna formateringsegenskaper för textdelen utan att ärvd information tillämpas. |
| [getText()](#getText--) | Hämtar eller anger vanlig text för en del. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger vanlig text för en del. |
| [getField()](#getField--) | Returnerar ett fält för denna del. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konverterar den här delen till ett automatiskt uppdaterat fält. |
| [addField(String internalString)](#addField-java.lang.String-) | Konverterar den här delen till ett automatiskt uppdaterat fält. |
| [removeField()](#removeField--) | Konverterar detta fältavsnitt till ett enkelt avsnitt. |
| [getRect()](#getRect--) | Hämtar koordinaterna för rektangeln som omger delen. |
| [getCoordinates()](#getCoordinates--) | Hämtar koordinaterna för början av delen. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Returnerar ett formateringsobjekt som innehåller explicit angivna formateringsegenskaper för textdelen utan att ärvd information tillämpas. Skrivskyddad [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Formateringsobjektet innehåller formateringsparametrarna som definierats endast för den aktuella delen, ärvd data tillämpas inte.

För att få de effektiva värdena inklusive ärvda, använd metoden [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Hämtar eller anger vanlig text för en del. Läs/skriv String.

Värde: Texten.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Hämtar eller anger vanlig text för en del. Läs/skriv String.

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


Konverterar den här delen till ett automatiskt uppdaterat fält.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Typ av fält [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Konverterar den här delen till ett automatiskt uppdaterat fält.

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
public abstract RectF getRect()
```


Hämtar koordinaterna för rektangeln som omger delen. Rektangeln inkluderar alla textrader i delen, inklusive tomma.

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


**Returnerar:**
android.graphics.RectF - Rektangel som omger delen android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```


Hämtar koordinaterna för början av delen. X-koordinaten för punkten representerar delens början från det första tecknet inklusive vänster sidobäring. Y-koordinaten inkluderar top-sidobäring.

**Returnerar:**
android.graphics.PointF - Koordinater för början av delen android.graphics.PointF