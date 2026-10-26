---
title: IPortion
second_title: Aspose.Slides Java API hivatkozás
description: Egy szövegbekezdésen belüli szövegrészt reprezentál.
type: docs
url: /hu/com.aspose.slides/iportion/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Egy szöveg bekezdésen belüli szövegrészt reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Visszaad egy formázási objektumot, amely a szövegrész explicit módon beállított formázási tulajdonságait tartalmazza, öröklődés nélkül. |
| [getText()](#getText--) | Lekérdezi vagy beállítja egy rész egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekérdezi vagy beállítja egy rész egyszerű szövegét. |
| [getField()](#getField--) | Visszaad a részhez tartozó mezőt. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Átalakítja ezt a részt az automatikusan frissített mezővé. |
| [addField(String internalString)](#addField-java.lang.String-) | Átalakítja ezt a részt az automatikusan frissített mezővé. |
| [removeField()](#removeField--) | Átalakítja ezt a mezőrészt egyszerű részzé. |
| [getRect()](#getRect--) | Lekéri a részt körülvevő téglalap koordinátáit. |
| [getCoordinates()](#getCoordinates--) | Lekéri a rész kezdetének koordinátáit. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Visszaad egy formázási objektumot, amely a szövegrész explicit módon beállított formázási tulajdonságait tartalmazza, öröklődés nélkül. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

A formázási objektum csak az aktuális részhez definiált formázási paramétereket tartalmazza, az örökölt adat nem alkalmazódik.

Az örökölt értékekkel együtt a hatékony értékek lekéréséhez használja a [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) metódust.

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Lekérdezi vagy beállítja egy rész egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Visszatérési érték:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Lekérdezi vagy beállítja egy rész egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```


Visszaad a részhez tartozó mezőt. Csak olvasható [IField](../../com.aspose.slides/ifield).

**Visszatérési érték:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Átalakítja ezt a részt az automatikusan frissített mezővé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Mező típusa [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Átalakítja ezt a részt az automatikusan frissített mezővé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| internalString | java.lang.String | A FieldTypeEx String belső neve |
### removeField() {#removeField--}
```
public abstract void removeField()
```


Átalakítja ezt a mezőrészt egyszerű részzé.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Lekéri a részt körülvevő téglalap koordinátáit. A téglalap tartalmazza a részben lévő összes szövegsort, beleértve az üreseket is.

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
java.awt.geom.Rectangle2D.Float - A részt körülvevő téglalap java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```


Lekéri a rész kezdetének koordinátáit. A pont X koordinátája a rész kezdetét jelöli az első karaktertől, beleértve a bal oldali távolságot. A Y koordináta tartalmazza a felső oldali távolságot.

**Visszatérési érték:**
java.awt.geom.Point2D.Float - A rész kezdetének koordinátái java.awt.geom.Point2D.Float