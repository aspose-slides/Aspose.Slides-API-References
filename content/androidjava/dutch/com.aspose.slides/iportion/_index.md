---
title: IPortion
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een gedeelte van tekst binnen een alinea voor.
type: docs
url: /nl/com.aspose.slides/iportion/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Stelt een gedeelte van tekst binnen een alinea voor.
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Retourneert een opmaakobject dat expliciet ingestelde opmaak-eigenschappen van het tekstgedeelte bevat zonder dat er overerving wordt toegepast. |
| [getText()](#getText--) | Haalt of stelt de platte tekst van een gedeelte in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt of stelt de platte tekst van een gedeelte in. |
| [getField()](#getField--) | Retourneert een veld van dit gedeelte. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [addField(String internalString)](#addField-java.lang.String-) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [removeField()](#removeField--) | Converteert dit veldgedeelte naar het eenvoudige gedeelte. |
| [getRect()](#getRect--) | Haal de coördinaten op van de rechthoek die het gedeelte omsluit. |
| [getCoordinates()](#getCoordinates--) | Haal de coördinaten op van het begin van het gedeelte. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Retourneert een opmaakobject dat expliciet ingestelde opmaak-eigenschappen van het tekstgedeelte bevat zonder dat er overerving wordt toegepast. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Het opmaakobject bevat alleen de voor het huidige gedeelte gedefinieerde opmaak-parameters; er wordt geen overgeërfde data toegepast.

Om de effectieve waarden inclusief overgeërfde waarden te krijgen, gebruik de [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective)-methode.

**Retour:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Haalt of stelt de platte tekst van een gedeelte in. Lezen/schrijven String.

Waarde: De tekst.

**Retour:**
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

**Retour:**
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

Converteert dit veldgedeelte naar het eenvoudige gedeelte.
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Haal de coördinaten op van de rechthoek die het gedeelte omsluit. De rechthoek omvat alle tekstregels in het gedeelte, inclusief lege.

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

**Retour:**
android.graphics.RectF - Rechthoek die het gedeelte omsluit android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

Haal de coördinaten op van het begin van het gedeelte. De X-coördinaat van het punt geeft het begin van het gedeelte aan vanaf het eerste teken, inclusief de linker-side-bearing. De Y-coördinaat omvat de boven-side-bearing.

**Retour:**
android.graphics.PointF - Coördinaten van het begin van het gedeelte android.graphics.PointF