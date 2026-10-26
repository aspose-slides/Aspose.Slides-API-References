---
title: IModernComment
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt einen Kommentar zu einer Folie dar.
type: docs
url: /de/com.aspose.slides/imoderncomment/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Stellt einen comment zu einer Folie dar.

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
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShape()](#getShape--) | Gibt ein shape zurück, das mit dem comment verknüpft ist. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Gibt die Startposition der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Gibt die Startposition der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Gibt die Länge der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Gibt die Länge der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. |
| [getStatus()](#getStatus--) | Gibt den Status des comment zurück oder setzt ihn. |
| [setStatus(byte value)](#setStatus-byte-) | Gibt den Status des comment zurück oder setzt ihn. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Gibt ein shape zurück, das mit dem comment verknüpft ist. Nur lesend [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Gibt die Startposition der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. Lesen/Schreiben int.

**Rückgabe:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Gibt die Startposition der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Gibt die Länge der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. Lesen/Schreiben int.

**Rückgabe:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Gibt die Länge der Textauswahl im Textrahmen zurück oder setzt sie, wenn der comment mit AutoShape verknüpft ist. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Gibt den Status des comment zurück oder setzt ihn. Lesen/Schreiben [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Rückgabe:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Gibt den Status des comment zurück oder setzt ihn. Lesen/Schreiben [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |