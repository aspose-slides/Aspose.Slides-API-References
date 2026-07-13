---
title: IParagraph
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un paragrafo di testo.
type: docs
url: /it/com.aspose.slides/iparagraph/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Rappresenta un paragrafo di testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPortions()](#getPortions--) | Restituisce la collezione di porzioni di testo. |
| [getParagraphFormat()](#getParagraphFormat--) | Restituisce l'oggetto di formattazione per questo paragrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce i run con la stessa formattazione. |
| [getText()](#getText--) | Ottiene o imposta il testo semplice di un paragrafo. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo semplice di un paragrafo. |
| [getRect()](#getRect--) | Ottiene le coordinate del rettangolo che delimita il paragrafo. |
| [getLinesCount()](#getLinesCount--) | Ottiene il numero di linee in un paragrafo. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specifica le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specifica le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Restituisce la collezione di porzioni di testo. Sola lettura [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Restituisce:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Restituisce l'oggetto di formattazione per questo paragrafo. Sola lettura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Restituisce:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Unisce i run con la stessa formattazione.

### getText() {#getText--}
```
public abstract String getText()
```


Ottiene o imposta il testo semplice di un paragrafo. Lettura/scrittura String.

Valore: Il testo.

**Restituisce:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Ottiene o imposta il testo semplice di un paragrafo. Lettura/scrittura String.

Valore: Il testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Ottiene le coordinate del rettangolo che delimita il paragrafo. Il rettangolo include tutte le linee di testo nel paragrafo, incluse quelle vuote.

**Restituisce:**
android.graphics.RectF - Rettangolo che delimita il paragrafo android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


Ottiene il numero di linee in un paragrafo.

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
int - Conteggio delle linee in un paragrafo
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Specifică le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima.

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Specifică le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo l'ultima.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |