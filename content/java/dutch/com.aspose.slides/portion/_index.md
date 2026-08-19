---
title: Portion
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een gedeelte van tekst binnen een tekstparagraaf.
type: docs
url: /nl/com.aspose.slides/portion/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Stelt een tekstdeel binnen een tekstopmaak voor.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [Portion()](#Portion--) | Initialiseert een nieuwe instantie van de class Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Initialiseert een nieuwe instantie van de class Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Initialiseert een nieuwe instantie van de class Portion. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Retourneert een formatteringsobject dat expliciet ingestelde opmaak-eigenschappen van het tekstdeel bevat zonder toepassing van overerving. |
| [getText()](#getText--) | Haalt de platte tekst van een deel op of stelt deze in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt de platte tekst van een deel op of stelt deze in. |
| [getField()](#getField--) | Retourneert een veld van dit deel. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converteert dit deel naar een automatisch bijgewerkt veld. |
| [addField(String internalString)](#addField-java.lang.String-) | Converteert dit deel naar een automatisch bijgewerkt veld. |
| [removeField()](#removeField--) | Converteert dit velddeel naar het eenvoudige deel. |
| [getRect()](#getRect--) | Haalt de coördinaten op van de rechthoek die het deel omsluit. |
| [getCoordinates()](#getCoordinates--) | Haalt de coördinaten op van het begin van het deel. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een tekst. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een tekst. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Initialiseert een nieuwe instantie van de class Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Initialiseert een nieuwe instantie van de class Portion.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Initialiseert een nieuwe instantie van de class Portion.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Retourneert een formatteringsobject dat expliciet ingestelde opmaak-eigenschappen van het tekstdeel bevat zonder toepassing van overerving. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Het formatteringsobject bevat alleen de voor dit deel gedefinieerde opmaak-parameters; overgeërfde gegevens worden niet toegepast.

Om de effectieve waarden inclusief overgeërfde waarden te krijgen, gebruik de [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective)-methode.

**Retour:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Haalt de platte tekst van een deel op of stelt deze in. Lezen/schrijven String.

Waarde: De tekst.

**Retour:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Haalt de platte tekst van een deel op of stelt deze in. Lezen/schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Retourneert een veld van dit deel. Alleen-lezen [IField](../../com.aspose.slides/ifield).

**Retour:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Converteert dit deel naar een automatisch bijgewerkt veld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Converteert dit deel naar een automatisch bijgewerkt veld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| internalString | java.lang.String | Interne naam van FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Converteert dit velddeel naar het eenvoudige deel.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Haalt de coördinaten op van de rechthoek die het deel omsluit. De rechthoek omvat alle tekstregels in het deel, inclusief lege regels.

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

**Retour:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Haalt de coördinaten op van het begin van het deel. De X-coördinaat van het punt geeft het begin van het deel weer vanaf het eerste teken, inclusief de linker-kantlijn. De Y-coördinaat omvat de bovenkant-kantlijn.

**Retour:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een tekst. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een tekst. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert het Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject