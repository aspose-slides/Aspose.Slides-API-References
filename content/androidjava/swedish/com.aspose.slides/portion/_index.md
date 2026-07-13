---
title: Portion
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en del av texten i ett textstycke.
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

Representerar en del av texten i ett textstycke.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Portion()](#Portion--) | Skapar en ny instans av Portion-klassen. |
| [Portion(String str)](#Portion-java.lang.String-) | Skapar en ny instans av Portion-klassen. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Skapar en ny instans av Portion-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Returnerar formateringsobjektet som innehåller explicit inställda formateringsegenskaper för textdelen utan ärvd formatering. |
| [getText()](#getText--) | Hämtar eller anger vanlig text för en del. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger vanlig text för en del. |
| [getField()](#getField--) | Returnerar ett fält för denna del. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konverterar denna del till ett automatiskt uppdaterat fält. |
| [addField(String internalString)](#addField-java.lang.String-) | Konverterar denna del till ett automatiskt uppdaterat fält. |
| [removeField()](#removeField--) | Konverterar detta fältsegment till ett enkelt segment. |
| [getRect()](#getRect--) | Hämta koordinaterna för rektangeln som omger delen. |
| [getCoordinates()](#getCoordinates--) | Hämta koordinaterna för början av delen. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för en text. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för en text. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Skapar en ny instans av Portion-klassen.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Skapar en ny instans av Portion-klassen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Skapar en ny instans av Portion-klassen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Returnerar formateringsobjektet som innehåller explicit inställda formateringsegenskaper för textdelen utan ärvd formatering. Skrivskyddad [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Formateringsobjektet innehåller enbart de formateringsparametrar som definierats för den aktuella delen, ärvd data tillämpas inte.

För att få de effektiva värdena inklusive ärvda, använd metoden [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Hämtar eller anger vanlig text för en del. Läs/skriv String.

Värde: Texten.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Hämtar eller anger vanlig text för en del. Läs/skriv String.

Värde: Texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Returnerar ett fält för denna del. Skrivskyddad [IField](../../com.aspose.slides/ifield).

**Returnerar:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Konverterar denna del till ett automatiskt uppdaterat fält.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Konverterar denna del till ett automatiskt uppdaterat fält.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| internalString | java.lang.String | Internt namn för FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Konverterar detta fältsegment till ett enkelt segment.

### getRect() {#getRect--}
```
public final RectF getRect()
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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Hämta koordinaterna för början av delen. X-koordinaten för punkten representerar delens början från det första tecknet inklusive vänster sidobärare. Y-koordinaten inkluderar övre sidobärare.

**Returnerar:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för en text. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för en text. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject