---
title: IPortion
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una porzione di testo all'interno di un paragrafo di testo.
type: docs
url: /it/com.aspose.slides/iportion/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Rappresenta una porzione di testo all'interno di un paragrafo di testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Restituisce un oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza eredità applicata. |
| [getText()](#getText--) | Ottiene o imposta il testo semplice di una porzione. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo semplice di una porzione. |
| [getField()](#getField--) | Restituisce un campo di questa porzione. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converte questa porzione in un campo aggiornato automaticamente. |
| [addField(String internalString)](#addField-java.lang.String-) | Converte questa porzione in un campo aggiornato automaticamente. |
| [removeField()](#removeField--) | Converte questa porzione di campo nella porzione semplice. |
| [getRect()](#getRect--) | Ottiene le coordinate del rettangolo che delimita la porzione. |
| [getCoordinates()](#getCoordinates--) | Ottiene le coordinate dell'inizio della porzione. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Restituisce un oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza eredità applicata. Solo lettura [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

L'oggetto di formattazione contiene i parametri di formattazione definiti solo per la porzione corrente, i dati ereditati non sono applicati.

Per ottenere i valori effettivi includendo quelli ereditati, usa il metodo [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Ottiene o imposta il testo semplice di una porzione. Lettura/scrittura String.

Valore: Il testo.

**Restituisce:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Ottiene o imposta il testo semplice di una porzione. Lettura/scrittura String.

Valore: Il testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

Restituisce un campo di questa porzione. Solo lettura [IField](../../com.aspose.slides/ifield).

**Restituisce:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Converte questa porzione in un campo aggiornato automaticamente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Tipo di campo [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Converte questa porzione in un campo aggiornato automaticamente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| internalString | java.lang.String | Nome interno del FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```

Converte questa porzione di campo nella porzione semplice.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Ottiene le coordinate del rettangolo che delimita la porzione. Il rettangolo include tutte le linee di testo nella porzione, incluse quelle vuote.

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


**Restituisce:**
java.awt.geom.Rectangle2D.Float - Rettangolo che delimita la porzione java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

Ottiene le coordinate dell'inizio della porzione. La coordinata X del punto rappresenta l'inizio della porzione dal primo carattere includendo il left side bearing. La coordinata Y include il top side bearing.

**Restituisce:**
java.awt.geom.Point2D.Float - Coordinate dell'inizio della porzione java.awt.geom.Point2D.Float