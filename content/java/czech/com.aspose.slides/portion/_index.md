---
title: Portion
second_title: Aspose.Slides pro Java - API reference
description: Zastupuje část textu uvnitř odstavce.
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

Zastupuje část textu uvnitř odstavce textu.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Portion()](#Portion--) | Inicializuje novou instanci třídy Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Inicializuje novou instanci třídy Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Inicializuje novou instanci třídy Portion. |

## Metody

| Metoda | Popis |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování části textu bez použité dědičnosti. |
| [getText()](#getText--) | Získává nebo nastavuje prostý text části. |
| [setText(String value)](#setText-java.lang.String-) | Získává nebo nastavuje prostý text části. |
| [getField()](#getField--) | Vrací pole této části. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Převede tuto část na automaticky aktualizované pole. |
| [addField(String internalString)](#addField-java.lang.String-) | Převede tuto část na automaticky aktualizované pole. |
| [removeField()](#removeField--) | Převede tuto část pole na jednoduchou část. |
| [getRect()](#getRect--) | Získá souřadnice obdélníku, který ohraničuje část. |
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

Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování části textu bez použité dědičnosti. Pouze pro čtení [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Objekt formátování obsahuje pouze parametry formátování definované pro aktuální část, zděděná data nejsou použita.

Pro získání efektivních hodnot včetně zděděných použijte metodu [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public final String getText()
```

Získává nebo nastavuje prostý text části. Číst/Zapisovat String.

Hodnota: Text.

**Vrací:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Získává nebo nastavuje prostý text části. Číst/Zapisovat String.

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
public final Rectangle2D.Float getRect()
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
java.awt.geom.Rectangle2D.Float

### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Získá souřadnice začátku části. Souřadnice X bodu představuje začátek části od prvního znaku včetně levého postranního okraje. Souřadnice Y zahrnuje horní postranní okraj.

**Vrací:**
java.awt.geom.Point2D.Float

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