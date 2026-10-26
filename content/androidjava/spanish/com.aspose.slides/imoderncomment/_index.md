---
title: IModernComment
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un comentario en una diapositiva.
type: docs
url: /es/com.aspose.slides/imoderncomment/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Representa un comentario en una diapositiva.

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
## Métodos

| Método | Descripción |
| --- | --- |
| [getShape()](#getShape--) | Devuelve una forma asociada al comentario. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Devuelve o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Devuelve o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Devuelve o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Devuelve o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [getStatus()](#getStatus--) | Devuelve o establece el estado del comentario. |
| [setStatus(byte value)](#setStatus-byte-) | Devuelve o establece el estado del comentario. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Devuelve una forma asociada al comentario. Solo lectura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Devuelve o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Devuelve:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Devuelve o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Devuelve o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Devuelve:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Devuelve o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Devuelve o establece el estado del comentario. Lectura/escritura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Devuelve:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Devuelve o establece el estado del comentario. Lectura/escritura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |