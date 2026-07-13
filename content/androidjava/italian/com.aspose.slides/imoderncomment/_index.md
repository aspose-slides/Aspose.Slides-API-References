---
title: IModernComment
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un commento su una diapositiva.
type: docs
url: /it/com.aspose.slides/imoderncomment/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Rappresenta un commento su una diapositiva.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShape()](#getShape--) | Restituisce una forma associata al commento. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Restituisce o imposta la posizione iniziale della selezione di testo nella casella di testo se il commento è associato a AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Restituisce o imposta la posizione iniziale della selezione di testo nella casella di testo se il commento è associato a AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Restituisce o imposta la lunghezza della selezione di testo nella casella di testo se il commento è associato a AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Restituisce o imposta la lunghezza della selezione di testo nella casella di testo se il commento è associato a AutoShape. |
| [getStatus()](#getStatus--) | Restituisce o imposta lo stato del commento. |
| [setStatus(byte value)](#setStatus-byte-) | Restituisce o imposta lo stato del commento. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Restituisce una forma associata al commento. Solo lettura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Restituisce o imposta la posizione iniziale della selezione di testo nella casella di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Restituisce:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Restituisce o imposta la posizione iniziale della selezione di testo nella casella di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Restituisce o imposta la lunghezza della selezione di testo nella casella di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Restituisce:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Restituisce o imposta la lunghezza della selezione di testo nella casella di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Restituisce o imposta lo stato del commento. Lettura/scrittura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Restituisce:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Restituisce o imposta lo stato del commento. Lettura/scrittura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |