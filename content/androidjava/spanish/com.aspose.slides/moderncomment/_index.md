---
title: ModernComment
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un comentario en una diapositiva.
type: docs
url: /es/com.aspose.slides/moderncomment/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Todas las interfaces implementadas:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
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
| [getTextSelectionStart()](#getTextSelectionStart--) | Obtiene o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Obtiene o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Obtiene o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Obtiene o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. |
| [getStatus()](#getStatus--) | Obtiene o establece el estado del comentario. |
| [setStatus(byte value)](#setStatus-byte-) | Obtiene o establece el estado del comentario. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

Devuelve una forma asociada al comentario. Solo lectura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Obtiene o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Devuelve:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Obtiene o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Obtiene o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Devuelve:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Obtiene o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Obtiene o establece el estado del comentario. Lectura/escritura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Devuelve:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Obtiene o establece el estado del comentario. Lectura/escritura [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject