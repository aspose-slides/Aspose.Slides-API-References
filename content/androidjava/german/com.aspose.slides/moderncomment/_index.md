---
title: ModernComment
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Kommentar auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/moderncomment/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Stellt einen Kommentar auf einer Folie dar.

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
| [getShape()](#getShape--) | Gibt ein Shape zurück, das mit dem Kommentar verknüpft ist. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Liest oder setzt die Startposition der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Liest oder setzt die Startposition der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Liest oder setzt die Länge der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Liest oder setzt die Länge der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. |
| [getStatus()](#getStatus--) | Liest oder setzt den Status des Kommentars. |
| [setStatus(byte value)](#setStatus-byte-) | Liest oder setzt den Status des Kommentars. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```


Gibt ein Shape zurück, das mit dem Kommentar verknüpft ist. Nur-Lesen [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


Liest oder setzt die Startposition der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. Lese/Schreib int.

**Rückgabe:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextPlacementStart(int value)
```


Liest oder setzt die Startposition der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


Liest oder setzt die Länge der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. Lese/Schreib int.

**Rückgabe:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


Liest oder setzt die Länge der Textauswahl im Textfeld, wenn der Kommentar mit einer AutoShape verknüpft ist. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


Liest oder setzt den Status des Kommentars. Lese/Schreib [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Rückgabe:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


Liest oder setzt den Status des Kommentars. Lese/Schreib [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject