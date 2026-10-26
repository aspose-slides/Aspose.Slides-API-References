---
title: IModernComment
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Kommentar auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/imoderncomment/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Repräsentiert einen Kommentar auf einer Folie.

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
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShape()](#getShape--) | Gibt eine Shape zurück, die dem Kommentar zugeordnet ist. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Gibt die Startposition der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar einer AutoShape zugeordnet ist. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Gibt die Startposition der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar einer AutoShape zugeordnet ist. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Gibt die Länge der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar einer AutoShape zugeordnet ist. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Gibt die Länge der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar einer AutoShape zugeordnet ist. |
| [getStatus()](#getStatus--) | Gibt den Status des Kommentars zurück oder setzt ihn. |
| [setStatus(byte value)](#setStatus-byte-) | Gibt den Status des Kommentars zurück oder setzt ihn. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Gibt eine Shape zurück, die dem Kommentar zugeordnet ist. Nur lesbar [IShape](../../com.aspose.slides/ishape).

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Gibt die Startposition der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar einer AutoShape zugeordnet ist. Schreib-/Lese-int.

**Rückgabewert:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Setzt oder gibt die Startposition der Textauswahl im Textfeld zurück, wenn der Kommentar einer AutoShape zugeordnet ist. Schreib-/Lese-int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Gibt die Länge der Textauswahl im Textfeld zurück oder setzt sie, wenn der Kommentar einer AutoShape zugeordnet ist. Schreib-/Lese-int.

**Rückgabewert:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Setzt oder gibt die Länge der Textauswahl im Textfeld zurück, wenn der Kommentar einer AutoShape zugeordnet ist. Schreib-/Lese-int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Gibt den Status des Kommentars zurück oder setzt ihn. Schreib-/Lese-[ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Rückgabewert:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Setzt oder gibt den Status des Kommentars zurück, wenn er einer AutoShape zugeordnet ist. Schreib-/Lese-[ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |