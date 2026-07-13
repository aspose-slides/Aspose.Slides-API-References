---
title: Portion
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje část textu uvnitř textového odstavce.
type: docs
url: /cs/com.aspose.slides/portion/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Reprezentuje část textu uvnitř textového odstavce.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Portion()](#Portion--) | Inicializuje novou instanci třídy Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Inicializuje novou instanci třídy Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Inicializuje novou instanci třídy Portion. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikované dědičnosti. |
| [getText()](#getText--) | Získá nebo nastaví prostý text části. |
| [setText(String value)](#setText-java.lang.String-) | Získá nebo nastaví prostý text části. |
| [getField()](#getField--) | Vrací pole této části. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Převede tuto část na automaticky aktualizované pole. |
| [addField(String internalString)](#addField-java.lang.String-) | Převede tuto část na automaticky aktualizované pole. |
| [removeField()](#removeField--) | Převede tuto část pole na jednoduchou část. |
| [getRect()](#getRect--) | Získá souřadnice obdélníku ohraničujícího část. |
| [getCoordinates()](#getCoordinates--) | Získá souřadnice začátku části. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek textu. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci textu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Inicializuje novou instanci třídy Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Inicializuje novou instanci třídy Portion.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Inicializuje novou instanci třídy Portion.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikované dědičnosti. Pouze pro čtení [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Objekt formátování obsahuje pouze parametry definované pro aktuální část, děděná data nejsou použita.

Pro získání efektivních hodnot včetně zděděných použijte metodu [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Získá nebo nastaví prostý text části. Číst/zapisovat String.

Hodnota: Text.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Získá nebo nastaví prostý text části. Číst/zapisovat String.

Hodnota: Text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Vrací pole této části. Pouze pro čtení [IField](../../com.aspose.slides/ifield).

**Vrací:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Převede tuto část na automaticky aktualizované pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Převede tuto část na automaticky aktualizované pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| internalString | java.lang.String | Interní název FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Převede tuto část pole na jednoduchou část.

### getRect() {#getRect--}
```
public final RectF getRect()
```

Získá souřadnice obdélníku ohraničujícího část. Obdélník zahrnuje všechny řádky textu v části, včetně prázdných.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Získá souřadnice začátku části. Souřadnice X bodu představuje začátek části od prvního znaku včetně levého okraje. Souřadnice Y zahrnuje horní okraj.

**Vrací:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek textu. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci textu. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject