---
title: Portion
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een gedeelte van tekst binnen een alinea voor.
type: docs
url: /nl/com.aspose.slides/portion/
---
**Overerving:**
java.lang.Object

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Stelt een gedeelte van tekst binnen een alinea voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Portion()](#Portion--) | Initialiseert een nieuwe instantie van de Portion klasse. |
| [Portion(String str)](#Portion-java.lang.String-) | Initialiseert een nieuwe instantie van de Portion klasse. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Initialiseert een nieuwe instantie van de Portion klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Retourneert een opmaakobject dat expliciet ingestelde opmaak-eigenschappen van het tekstgedeelte bevat, zonder overerving toegepast. |
| [getText()](#getText--) | Haalt of stelt de platte tekst van een gedeelte in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt of stelt de platte tekst van een gedeelte in. |
| [getField()](#getField--) | Retourneert een veld van dit gedeelte. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converteert dit gedeelte naar een automatisch bijgewerkt veld. |
| [addField(String internalString)](#addField-java.lang.String-) | Converteert dit gedeelte naar een automatisch bijgewerkt veld. |
| [removeField()](#removeField--) | Converteert dit veldgedeelte naar het eenvoudige gedeelte. |
| [getRect()](#getRect--) | Haalt de coördinaten op van de rechthoek die het gedeelte begrenst. |
| [getCoordinates()](#getCoordinates--) | Haalt de coördinaten op van het begin van het gedeelte. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende slide van een tekst. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een tekst. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Initialiseert een nieuwe instantie van de Portion klasse.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Initialiseert een nieuwe instantie van de Portion klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Initialiseert een nieuwe instantie van de Portion klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Retourneert een opmaakobject dat expliciet ingestelde opmaak-eigenschappen van het tekstgedeelte bevat, zonder overerving toegepast. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Het opmaakobject bevat alleen de opmaakparameters die voor het huidige gedeelte zijn gedefinieerd; overgeërfde gegevens worden niet toegepast.

Om de effectieve waarden, inclusief overgeërfde, op te halen, gebruikt u de [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective)-methode.

**Retourneert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Haalt of stelt de platte tekst van een gedeelte in. Lezen/schrijven String.

Waarde: De tekst.

**Retourneert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Haalt of stelt de platte tekst van een gedeelte in. Lezen/schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Retourneert een veld van dit gedeelte. Alleen-lezen [IField](../../com.aspose.slides/ifield).

**Retourneert:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Converteert dit gedeelte naar een automatisch bijgewerkt veld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Converteert dit gedeelte naar een automatisch bijgewerkt veld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| internalString | java.lang.String | Interne naam van FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Converteert dit veldgedeelte naar het eenvoudige gedeelte.

### getRect() {#getRect--}
```
public final RectF getRect()
```

Haalt de coördinaten op van de rechthoek die het gedeelte begrenst. De rechthoek omvat alle tekstregels in het gedeelte, inclusief lege regels.

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

**Retourneert:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Haalt de coördinaten op van het begin van het gedeelte. De X-coördinaat van het punt geeft het begin van het gedeelte aan, beginnend bij het eerste teken inclusief linker-side-bearing. De Y-coördinaat omvat boven-side-bearing.

**Retourneert:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende slide van een tekst. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een tekst. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert het Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject