---
title: IPortion
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy szöveg bekezdésen belüli szövegrészletet képvisel.
type: docs
url: /hu/com.aspose.slides/iportion/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Egy szövegdobozon belüli szövegrészletet képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Visszaad egy formázási objektumot, amely tartalmazza a szövegrészletre kifejezetten beállított formázási tulajdonságokat, öröklődés nélkül. |
| [getText()](#getText--) | Lekéri vagy beállítja egy részlet egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja egy részlet egyszerű szövegét. |
| [getField()](#getField--) | Visszaad egy mezőt ebben a részletben. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Átalakítja ezt a részletet automatikusan frissülő mezővé. |
| [addField(String internalString)](#addField-java.lang.String-) | Átalakítja ezt a részletet automatikusan frissülő mezővé. |
| [removeField()](#removeField--) | Átalakítja ezt a mező részletet egyszerű részletté. |
| [getRect()](#getRect--) | Lekéri a részletet határoló téglalap koordinátáit. |
| [getCoordinates()](#getCoordinates--) | Lekéri a részlet elejének koordinátáit. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Visszaad egy formázási objektumot, amely tartalmazza a szövegrészletre kifejezetten beállított formázási tulajdonságokat, öröklődés nélkül. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

A formázási objektum csak az aktuális részlethez definiált formázási paramétereket tartalmazza, az örökölt adatok nem kerülnek alkalmazásra.

A hatékony értékek, beleértve az örökölt értékeket, lekéréséhez használja a [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) metódust.

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Lekéri vagy beállítja egy részlet egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Visszatér:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Lekéri vagy beállítja egy részlet egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```


Visszaad egy mezőt ebben a részletben. Csak olvasható [IField](../../com.aspose.slides/ifield).

**Visszatér:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Átalakítja ezt a részletet automatikusan frissülő mezővé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Mező típusa [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Átalakítja ezt a részletet automatikusan frissülő mezővé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| internalString | java.lang.String | A FieldTypeEx String belső neve |
### removeField() {#removeField--}
```
public abstract void removeField()
```


Átalakítja ezt a mező részletet egyszerű részletté.

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Lekéri a részletet határoló téglalap koordinátáit. A téglalap tartalmazza a részletben lévő összes szövegsort, beleértve az üres sorokat is.

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


**Visszatér:**
android.graphics.RectF - A részletet határoló téglalap android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```


Lekéri a részlet elejének koordinátáit. A pont X koordinátája a részlet kezdetét jelöli az első karaktertől, beleértve a bal oldali távolságot. A Y koordináta tartalmazza a felső oldali távolságot.

**Visszatér:**
android.graphics.PointF - A részlet elejének koordinátái android.graphics.PointF