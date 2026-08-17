---
title: IModernComment
second_title: Referência da API Aspose.Slides for Java
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
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getShape()](#getShape--) | Retorna uma forma associada ao comentário. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Retorna ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Retorna ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Retorna ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Retorna ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [getStatus()](#getStatus--) | Retorna ou define o status do comentário. |
| [setStatus(byte value)](#setStatus-byte-) | Retorna ou define o status do comentário. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Retorna uma forma associada ao comentário. Somente leitura [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Retorna ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/gravação int.

**Retorna:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Retorna ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Retorna ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/gravação int.

**Retorna:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Retorna ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/gravação int.

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