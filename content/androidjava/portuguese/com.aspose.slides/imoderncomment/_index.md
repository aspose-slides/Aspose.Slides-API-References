---
title: IModernComment
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa um comentário em um slide.
type: docs
url: /pt/com.aspose.slides/imoderncomment/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Representa um comentário em um slide.

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

| Método | Descrição |
| --- | --- |
| [getShape()](#getShape--) | Returns a shape associated with the comment. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Returns or sets starting position of text selection in text frame if the comment associated with AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Returns or sets starting position of text selection in text frame if the comment associated with AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Returns or sets text selection length in text frame if the comment associated with AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Returns or sets text selection length in text frame if the comment associated with AutoShape. |
| [getStatus()](#getStatus--) | Returns or sets the status of the comment. |
| [setStatus(byte value)](#setStatus-byte-) | Returns or sets the status of the comment. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Retorna uma shape associada ao comentário. Somente leitura [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Retorna ou define a posição inicial da seleção de texto no frame de texto se o comentário estiver associado a AutoShape. Leitura/gravação int.

**Retorna:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Retorna ou define a posição inicial da seleção de texto no frame de texto se o comentário estiver associado a AutoShape. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Retorna ou define o comprimento da seleção de texto no frame de texto se o comentário estiver associado a AutoShape. Leitura/gravação int.

**Retorna:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Retorna ou define o comprimento da seleção de texto no frame de texto se o comentário estiver associado a AutoShape. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Retorna ou define o status do comentário. Leitura/gravação [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Retorna:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Retorna ou define o status do comentário. Leitura/gravação [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |