---
title: ModernComment
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un commento su una diapositiva.
type: docs
url: /it/com.aspose.slides/moderncomment/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Tutte le interfacce implementate:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
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
| [getTextSelectionStart()](#getTextSelectionStart--) | Ottiene o imposta la posizione iniziale della selezione del testo nel frame di testo se il commento è associato a AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Ottiene o imposta la posizione iniziale della selezione del testo nel frame di testo se il commento è associato a AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Ottiene o imposta la lunghezza della selezione del testo nel frame di testo se il commento è associato a AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Ottiene o imposta la lunghezza della selezione del testo nel frame di testo se il commento è associato a AutoShape. |
| [getStatus()](#getStatus--) | Ottiene o imposta lo stato del commento. |
| [setStatus(byte value)](#setStatus-byte-) | Ottiene o imposta lo stato del commento. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```


Restituisce una forma associata al commento. Solo lettura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


Ottiene o imposta la posizione iniziale della selezione del testo nel frame di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Restituisce:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


Ottiene o imposta la posizione iniziale della selezione del testo nel frame di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


Ottiene o imposta la lunghezza della selezione del testo nel frame di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Restituisce:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


Ottiene o imposta la lunghezza della selezione del testo nel frame di testo se il commento è associato a AutoShape. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


Ottiene o imposta lo stato del commento. Lettura/scrittura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Restituisce:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


Ottiene o imposta lo stato del commento. Lettura/scrittura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject