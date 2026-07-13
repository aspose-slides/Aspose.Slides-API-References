---
title: IModernComment
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje komentarz na slajdzie.
type: docs
url: /pl/com.aspose.slides/imoderncomment/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Reprezentuje komentarz na slajdzie.

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
## Metody

| Method | Description |
| --- | --- |
| [getShape()](#getShape--) | Zwraca kształt powiązany z komentarzem. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Zwraca lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Zwraca lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Zwraca lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Zwraca lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. |
| [getStatus()](#getStatus--) | Zwraca lub ustawia status komentarza. |
| [setStatus(byte value)](#setStatus-byte-) | Zwraca lub ustawia status komentarza. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Zwraca kształt powiązany z komentarzem. Tylko do odczytu [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Zwraca lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Zwraca:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Zwraca lub ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Zwraca lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Zwraca:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Zwraca lub ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z AutoShape. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Zwraca lub ustawia status komentarza. Odczyt/zapis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Zwraca:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Zwraca lub ustawia status komentarza. Odczyt/zapis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |