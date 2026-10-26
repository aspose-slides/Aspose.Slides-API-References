---
title: IPortion
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje část textu uvnitř textového odstavce.
type: docs
url: /cs/com.aspose.slides/iportion/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Reprezentuje část textu uvnitř textového odstavce.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikace dědičnosti. |
| [getText()](#getText--) | Získá nebo nastaví prostý text části. |
| [setText(String value)](#setText-java.lang.String-) | Získá nebo nastaví prostý text části. |
| [getField()](#getField--) | Vrací pole této části. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Převede tuto část na automaticky aktualizované pole. |
| [addField(String internalString)](#addField-java.lang.String-) | Převede tuto část na automaticky aktualizované pole. |
| [removeField()](#removeField--) | Převede tuto část pole na jednoduchou část. |
| [getRect()](#getRect--) | Získá souřadnice obdélníku, který ohraničuje část. |
| [getCoordinates()](#getCoordinates--) | Získá souřadnice začátku části. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikace dědičnosti. Pouze ke čtení [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Objekt formátování obsahuje parametry formátování definované pouze pro aktuální část, zděděná data nejsou použita.

Pro získání efektivních hodnot včetně zděděných použijte metodu [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Získá nebo nastaví prostý text části. Čtení/zápis String.

Hodnota: Text.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Získá nebo nastaví prostý text části. Čtení/zápis String.

Hodnota: Text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

Vrací pole této části. Pouze ke čtení [IField](../../com.aspose.slides/ifield).

**Vrací:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Převede tuto část na automaticky aktualizované pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Typ pole [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Převede tuto část na automaticky aktualizované pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| internalString | java.lang.String | Interní název FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```

Převede tuto část pole na jednoduchou část.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Získá souřadnice obdélníku, který ohraničuje část. Obdélník zahrnuje všechny řádky textu v části, včetně prázdných.

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


**Vrací:**
java.awt.geom.Rectangle2D.Float - Obdélník, který ohraničuje část java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

Získá souřadnice začátku části. Souřadnice X bodu představuje začátek části od prvního znaku včetně levého odsazení. Souřadnice Y zahrnuje horní odsazení.

**Vrací:**
java.awt.geom.Point2D.Float - Souřadnice začátku části java.awt.geom.Point2D.Float