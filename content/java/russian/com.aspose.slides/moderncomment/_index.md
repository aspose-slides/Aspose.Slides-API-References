---
title: ModernComment
second_title: Справочник API Aspose.Slides для Java
description: Представляет комментарий на слайде.
type: docs
url: /ru/com.aspose.slides/moderncomment/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Все реализованные интерфейсы:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
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
| [getTextSelectionStart()](#getTextSelectionStart--) | Получает или задает начальную позицию выделения текста во фрейме текста, если комментарий связан с AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Получает или задает начальную позицию выделения текста во фрейме текста, если комментарий связан с AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Получает или задает длину выделения текста во фрейме текста, если комментарий связан с AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Получает или задает длину выделения текста во фрейме текста, если комментарий связан с AutoShape. |
| [getStatus()](#getStatus--) | Получает или задает статус комментария. |
| [setStatus(byte value)](#setStatus-byte-) | Получает или задает статус комментария. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Возвращает форму, связанную с комментарием. Только для чтения [IShape](../../com.aspose.slides/ishape).

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Получает или задает начальную позицию выделения текста во фрейме текста, если комментарий связан с AutoShape. Чтение/запись int.

**Возвращает:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Получает или задает начальную позицию выделения текста во фрейме текста, если комментарий связан с AutoShape. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Получает или задает длину выделения текста во фрейме текста, если комментарий связан с AutoShape. Чтение/запись int.

**Возвращает:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Получает или задает длину выделения текста во фрейме текста, если комментарий связан с AutoShape. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Получает или задает статус комментария. Чтение/запись [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Возвращает:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Получает или задает статус комментария. Чтение/запись [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject