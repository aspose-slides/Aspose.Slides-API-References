---
title: Paragraph
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta un paragrafo di testo.
type: docs
url: /it/com.aspose.slides/paragraph/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Rappresenta un paragrafo di testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inizializza una nuova istanza della classe Paragraph con le proprietà predefinite. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Costruttore di copia che inizializza una nuova istanza di una classe Paragraph. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPortions()](#getPortions--) | Restituisce la collezione di porzioni di testo. |
| [getParagraphFormat()](#getParagraphFormat--) | Restituisce l'oggetto di formattazione per questo paragrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce le sequenze con la stessa formattazione. |
| [getText()](#getText--) | Ottiene o imposta il testo semplice di un paragrafo. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo semplice di un paragrafo. |
| [getRect()](#getRect--) | Ottiene le coordinate del rettangolo che delimita il paragrafo. |
| [getLinesCount()](#getLinesCount--) | Ottiene il numero di righe in un paragrafo. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specifica le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specifica le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore di un paragrafo. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di un paragrafo. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Inizializza una nuova istanza della classe Paragraph con le proprietà predefinite.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Costruttore di copia che inizializza una nuova istanza di una classe Paragraph.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Restituisce la collezione di porzioni di testo. Solo lettura [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Restituisce:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Restituisce l'oggetto di formattazione per questo paragrafo. Solo lettura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

L'oggetto di formattazione contiene i parametri di formattazione definiti solo per il paragrafo corrente, i dati ereditati non vengono applicati.

Per ottenere i valori effettivi inclusi quelli ereditati, utilizzare il metodo [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Restituisce:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Unisce le sequenze con la stessa formattazione.

### getText() {#getText--}
```
public final String getText()
```

Ottiene o imposta il testo semplice di un paragrafo. Lettura/scrittura String.

Valore: Il testo.

**Restituisce:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Ottiene o imposta il testo semplice di un paragrafo. Lettura/scrittura String.

Valore: Il testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Ottiene le coordinate del rettangolo che delimita il paragrafo. Il rettangolo include tutte le righe di testo nel paragrafo, incluse quelle vuote.

**Restituisce:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Ottiene il numero di righe in un paragrafo.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
int - Conteggio delle righe in un paragrafo
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Specifică le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima.

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Specifică le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva genitore di un paragrafo. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione genitore di un paragrafo. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)