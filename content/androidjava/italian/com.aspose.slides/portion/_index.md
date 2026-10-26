---
title: Portion
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una porzione di testo all'interno di un paragrafo di testo.
type: docs
url: /it/com.aspose.slides/portion/
---
**Eredità:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Rappresenta una porzione di testo all'interno di un paragrafo di testo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Portion()](#Portion--) | Inizializza una nuova istanza della classe Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Inizializza una nuova istanza della classe Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Inizializza una nuova istanza della classe Portion. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza eredità applicata. |
| [getText()](#getText--) | Ottiene o imposta il testo semplice di una porzione. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo semplice di una porzione. |
| [getField()](#getField--) | Restituisce un campo di questa porzione. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converte questa porzione nel campo aggiornato automaticamente. |
| [addField(String internalString)](#addField-java.lang.String-) | Converte questa porzione nel campo aggiornato automaticamente. |
| [removeField()](#removeField--) | Converte questa porzione di campo nella porzione semplice. |
| [getRect()](#getRect--) | Ottiene le coordinate del rettangolo che delimita la porzione. |
| [getCoordinates()](#getCoordinates--) | Ottiene le coordinate dell'inizio della porzione. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva principale del testo. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione principale del testo. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Portion() {#Portion--}
```
public Portion()
```

Inizializza una nuova istanza della classe Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Inizializza una nuova istanza della classe Portion.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Inizializza una nuova istanza della classe Portion.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza eredità applicata. Solo lettura [IPortionFormat](../../com.aspose.slides/iportionformat).

L'oggetto di formattazione contiene i parametri di formattazione definiti solo per la porzione corrente, i dati ereditati non sono applicati.

Per ottenere i valori effettivi includendo quelli ereditati, utilizzare il metodo [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public final String getText()
```

Ottiene o imposta il testo semplice di una porzione. Lettura/Scrittura String.

Valore: Il testo.

**Restituisce:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Ottiene o imposta il testo semplice di una porzione. Lettura/Scrittura String.

Valore: Il testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Restituisce un campo di questa porzione. Solo lettura [IField](../../com.aspose.slides/ifield).

**Restituisce:**
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Converte questa porzione nel campo aggiornato automaticamente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Converte questa porzione nel campo aggiornato automaticamente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| internalString | java.lang.String | Nome interno del FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Converte questa porzione di campo nella porzione semplice.

### getRect() {#getRect--}
```
public final RectF getRect()
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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
android.graphics.RectF

### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Ottiene le coordinate dell'inizio della porzione. La coordinata X del punto rappresenta l'inizio della porzione dal primo carattere includendo l'offset laterale sinistro. La coordinata Y include l'offset superiore.

**Restituisce:**
android.graphics.PointF

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva principale del testo. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione principale del testo. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject