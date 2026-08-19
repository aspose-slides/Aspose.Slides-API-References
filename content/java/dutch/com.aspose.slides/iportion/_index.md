---
title: IPortion
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een gedeelte van tekst binnen een tekstparagraaf voor.
type: docs
url: /nl/com.aspose.slides/iportion/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Stelt een gedeelte van tekst binnen een tekstparagraaf voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Retourneert een opmaakobject dat expliciet ingestelde opmaak-eigenschappen van het tekstddeel bevat, zonder toegepaste overerving. |
| [getText()](#getText--) | Haalt of stelt de platte tekst van een gedeelte in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt of stelt de platte tekst van een gedeelte in. |
| [getField()](#getField--) | Retourneert een veld van dit gedeelte. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [addField(String internalString)](#addField-java.lang.String-) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [removeField()](#removeField--) | Converteert dit veld-gedeelte naar het eenvoudige gedeelte. |
| [getRect()](#getRect--) | Haalt de coördinaten op van de rechthoek die het gedeelte omsluit. |
| [getCoordinates()](#getCoordinates--) | Haalt de coördinaten op van het begin van het gedeelte. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Retourneert een opmaakobject dat expliciet ingestelde opmaak-eigenschappen van het tekstddeel bevat, zonder toegepaste overerving. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Het opmaakobject bevat alleen de opmaakparameters die voor het huidige gedeelte zijn gedefinieerd; geërfde gegevens worden niet toegepast.

Om de effectieve waarden inclusief geërfde waarden te verkrijgen, gebruik de [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective)-methode.

**Retourneert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Haalt of stelt de platte tekst van een gedeelte in. Lezen/schrijven String.

Waarde: De tekst.

**Retourneert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Haalt of stelt de platte tekst van een gedeelte in. Lezen/schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```


Retourneert een veld van dit gedeelte. Alleen-lezen [IField](../../com.aspose.slides/ifield).

**Retourneert:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Converteert dit gedeelte naar het automatisch bijgewerkte veld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Type van veld [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Converteert dit gedeelte naar het automatisch bijgewerkte veld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| internalString | java.lang.String | Interne naam van FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```


Converteert dit veld-gedeelte naar het eenvoudige gedeelte.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Haalt de coördinaten op van de rechthoek die het gedeelte omsluit. De rechthoek omvat alle tekstregels in het gedeelte, inclusief lege regels.

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


**Retourneert:**
java.awt.geom.Rectangle2D.Float - Rechthoek die het gedeelte omsluit java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```


Haalt de coördinaten op van het begin van het gedeelte. De X-coördinaat van het punt geeft het begin van het gedeelte weer vanaf het eerste teken, inclusief de linkerkant-bearing. De Y-coördinaat omvat de bovenkant-bearing.

**Retourneert:**
java.awt.geom.Point2D.Float - Coördinaten van het begin van het gedeelte java.awt.geom.Point2D.Float