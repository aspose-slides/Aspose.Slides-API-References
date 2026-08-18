---
title: Portion
second_title: Aspose.Slides for Java API Referenciája
description: Egy szövegdobozon belüli szövegrészletet képvisel.
type: docs
url: /hu/com.aspose.slides/portion/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Egy szövegdobozon belüli szövegrészletet képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Portion()](#Portion--) | Új példányt hoz létre a Portion osztályból. |
| [Portion(String str)](#Portion-java.lang.String-) | Új példányt hoz létre a Portion osztályból. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Új példányt hoz létre a Portion osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Formázási objektumot ad vissza, amely a szövegrészlet explicit módon beállított formázási tulajdonságait tartalmazza, öröklődés nélkül. |
| [getText()](#getText--) | A részlet egyszerű szövegét adja vissza vagy állítja be. |
| [setText(String value)](#setText-java.lang.String-) | A részlet egyszerű szövegét adja vissza vagy állítja be. |
| [getField()](#getField--) | Mezőt ad vissza a részletből. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Átalakítja a részletet automatikusan frissített mezővé. |
| [addField(String internalString)](#addField-java.lang.String-) | Átalakítja a részletet automatikusan frissített mezővé. |
| [removeField()](#removeField--) | Átalakítja ezt a mező részletet egyszerű részletté. |
| [getRect()](#getRect--) | A részletet körülhatároló téglalap koordinátáit adja vissza. |
| [getCoordinates()](#getCoordinates--) | A részlet elejének koordinátáit adja vissza. |
| [getSlide()](#getSlide--) | A szöveg szülődi slide-ot adja vissza. |
| [getPresentation()](#getPresentation--) | A szöveg szülő prezentációját adja vissza. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Új példányt hoz létre a Portion osztályból.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Új példányt hoz létre a Portion osztályból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Új példányt hoz létre a Portion osztályból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Formázási objektumot ad vissza, amely a szövegrészlet explicit módon beállított formázási tulajdonságait tartalmazza, öröklődés nélkül. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

A formázási objektum csak a jelenlegi részlethez definiált formázási paramétereket tartalmazza, az örökölt adat nem kerül alkalmazásra.

Az örökölt értékeket is tartalmazó hatékony értékek lekéréséhez használja a [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) metódust.

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

A részlet egyszerű szövegét adja vissza vagy állítja be. Olvasás/írás String.

Érték: A szöveg.

**Visszatérési érték:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

A részlet egyszerű szövegét adja vissza vagy állítja be. Olvasás/írás String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Mezőt ad vissza a részletből. Csak olvasható [IField](../../com.aspose.slides/ifield).

**Visszatérési érték:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Átalakítja a részletet automatikusan frissített mezővé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Átalakítja a részletet automatikusan frissített mezővé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| internalString | java.lang.String | A FieldType belső neve. |

### removeField() {#removeField--}
```
public final void removeField()
```

Átalakítja ezt a mező részletet egyszerű részletté.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

A részletet körülhatároló téglalap koordinátáit adja vissza. A téglalap tartalmazza a részlet összes szövegsorát, beleértve az üres sorokat is.

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

**Visszatérési érték:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

A részlet elejének koordinátáit adja vissza. A pont X koordinátája a részlet kezdetét jelöli az első karaktertől, beleértve a baloldali keretet. Az Y koordináta a felső keretet tartalmazza.

**Visszatérési érték:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

A szöveg szülődi slide-ot adja vissza. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

A szöveg szülő prezentációját adja vissza. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate objektumot ad vissza. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject