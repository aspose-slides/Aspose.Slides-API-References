---
title: Portion
second_title: Aspose.Slides Androidra a Java API referenciája alapján
description: Egy szövegbekezdésen belüli szövegrészletet képvisel.
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

A szövegbekezdésen belüli szövegrészletet képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Portion()](#Portion--) | Új példányt hoz létre a Portion osztályból. |
| [Portion(String str)](#Portion-java.lang.String-) | Új példányt hoz létre a Portion osztályból. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Új példányt hoz létre a Portion osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Visszaad egy formázási objektumot, amely a szövegrészlet expliciten beállított formázási tulajdonságait tartalmazza, öröklődés nélkül. |
| [getText()](#getText--) | Lekéri vagy beállítja a részlet egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja a részlet egyszerű szövegét. |
| [getField()](#getField--) | Visszaad egy mezőt ebben a részletben. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Átalakítja ezt a részletet egy automatikusan frissített mezővé. |
| [addField(String internalString)](#addField-java.lang.String-) | Átalakítja ezt a részletet egy automatikusan frissített mezővé. |
| [removeField()](#removeField--) | Átalakítja ezt a mező részletet egyszerű részletté. |
| [getRect()](#getRect--) | Lekéri a részletet korlátozó téglalap koordinátáit. |
| [getCoordinates()](#getCoordinates--) | Lekéri a részlet kezdetének koordinátáit. |
| [getSlide()](#getSlide--) | Visszaadja a szöveg szülődiapozitívját. |
| [getPresentation()](#getPresentation--) | Visszaadja a szöveg szülőprezentációját. |
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


Visszaad egy formázási objektumot, amely a szövegrészlet expliciten beállított formázási tulajdonságait tartalmazza, öröklődés nélkül. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

A formázási objektum csak a jelenlegi részlethez definiált formázási paramétereket tartalmazza, az örökölt adatok nem kerülnek alkalmazásra.

Az örökölt értékeket is tartalmazó hatékony értékek lekéréséhez használja a [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) metódust.

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


Lekéri vagy beállítja a részlet egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Visszatérési érték:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Lekéri vagy beállítja a részlet egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


Visszaad egy mezőt ebben a részletben. Csak olvasható [IField](../../com.aspose.slides/ifield).

**Visszatérési érték:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


Átalakítja ezt a részletet egy automatikusan frissített mezővé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


Átalakítja ezt a részletet egy automatikusan frissített mezővé.

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
public final RectF getRect()
```


Lekéri a részletet korlátozó téglalap koordinátáit. A téglalap a részletben lévő összes szövegsort tartalmazza, beleértve az üreseket is.

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


**Visszatérési érték:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```


Lekéri a részlet kezdetének koordinátáit. A pont X koordinátája a részlet kezdetét jelöli az első karaktertől, beleértve a bal oldali távolságot. A Y koordináta a felső oldali távolságot tartalmazza.

**Visszatérési érték:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Visszaadja a szöveg szülődiapozitívját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Visszaadja a szöveg szülőprezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject