---
title: IModernComment
second_title: Справочник API Aspose.Slides для Java
description: Представляет комментарий на слайде.
type: docs
url: /ru/com.aspose.slides/imoderncomment/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Представляет комментарий на слайде.

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

## Методы

| Метод | Описание |
| --- | --- |
| [getShape()](#getShape--) | Возвращает форму, связанную с комментарием. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Возвращает или устанавливает начальную позицию выделения текста в текстовом кадре, если комментарий связан с AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Возвращает или устанавливает начальную позицию выделения текста в текстовом кадре, если комментарий связан с AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Возвращает или устанавливает длину выделения текста в текстовом кадре, если комментарий связан с AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Возвращает или устанавливает длину выделения текста в текстовом кадре, если комментарий связан с AutoShape. |
| [getStatus()](#getStatus--) | Возвращает или устанавливает статус комментария. |
| [setStatus(byte value)](#setStatus-byte-) | Возвращает или устанавливает статус комментария. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Возвращает форму, связанную с комментарием. Только для чтения [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Возвращает или устанавливает начальную позицию выделения текста в текстовом кадре, если комментарий связан с AutoShape. Чтение/запись int.

**Возвращаемое значение:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Возвращает или устанавливает начальную позицию выделения текста в текстовом кадре, если комментарий связан с AutoShape. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Возвращает или устанавливает длину выделения текста в текстовом кадре, если комментарий связан с AutoShape. Чтение/запись int.

**Возвращаемое значение:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Возвращает или устанавливает длину выделения текста в текстовом кадре, если комментарий связан с AutoShape. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Возвращает или устанавливает статус комментария. Чтение/запись [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Возвращаемое значение:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Возвращает или устанавливает статус комментария. Чтение/запись [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |