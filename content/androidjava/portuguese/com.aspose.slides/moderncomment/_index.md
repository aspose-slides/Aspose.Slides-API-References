---
title: ModernComment
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um comentário em um slide.
type: docs
url: /pt/com.aspose.slides/moderncomment/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
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
| [getShape()](#getShape--) | Retorna uma forma associada ao comentário. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Obtém ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Obtém ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Obtém ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Obtém ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. |
| [getStatus()](#getStatus--) | Obtém ou define o status do comentário. |
| [setStatus(byte value)](#setStatus-byte-) | Obtém ou define o status do comentário. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Retorna uma forma associada ao comentário. Somente leitura [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Obtém ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/Escrita int.

**Retorna:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Obtém ou define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/Escrita int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Obtém ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/Escrita int.

**Retorna:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Obtém ou define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado ao AutoShape. Leitura/Escrita int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Obtém ou define o status do comentário. Leitura/Escrita [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Retorna:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Obtém ou define o status do comentário. Leitura/Escrita [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject