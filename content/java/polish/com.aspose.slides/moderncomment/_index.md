---
title: ModernComment
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje komentarz na slajdzie.
type: docs
url: /pl/com.aspose.slides/moderncomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**All Implemented Interfaces:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Represents a comment on a slide.

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
## Metody

| Metoda | Opis |
| --- | --- |
| [getShape()](#getShape--) | Returns a shape associated with the comment. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Pobiera lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Pobiera lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Pobiera lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Pobiera lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [getStatus()](#getStatus--) | Pobiera lub ustawia status komentarza. |
| [setStatus(byte value)](#setStatus-byte-) | Pobiera lub ustawia status komentarza. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```


Returns a shape associated with the comment. Tylko do odczytu [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


Pobiera lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Zwraca:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


Pobiera lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


Pobiera lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Zwraca:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


Pobiera lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


Pobiera lub ustawia status komentarza. Odczyt/zapis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Zwraca:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


Pobiera lub ustawia status komentarza. Odczyt/zapis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject