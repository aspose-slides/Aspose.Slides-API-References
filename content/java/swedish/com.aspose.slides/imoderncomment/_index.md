---
title: IModernComment
second_title: Aspose.Slides för Java API-referens
description: Representerar en kommentar på en bild.
type: docs
url: /sv/com.aspose.slides/imoderncomment/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Representerar en kommentar på en bild.

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
## Metoder

| Method | Description |
| --- | --- |
| [getShape()](#getShape--) | Returnerar en shape som är associerad med kommentaren. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Returnerar eller anger startposition för textmarkering i textramen om kommentaren är associerad med en AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Returnerar eller anger startposition för textmarkering i textramen om kommentaren är associerad med en AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Returnerar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med en AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Returnerar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med en AutoShape. |
| [getStatus()](#getStatus--) | Returnerar eller anger statusen för kommentaren. |
| [setStatus(byte value)](#setStatus-byte-) | Returnerar eller anger statusen för kommentaren. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Returnerar en shape som är associerad med kommentaren. Skrivskyddad [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Returnerar eller anger startposition för textmarkering i textramen om kommentaren är associerad med en AutoShape. Läs/skriv int.

**Returnerar:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Returnerar eller anger startposition för textmarkering i textramen om kommentaren är associerad med en AutoShape. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Returnerar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med en AutoShape. Läs/skriv int.

**Returnerar:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Returnerar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med en AutoShape. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Returnerar eller anger statusen för kommentaren. Läs/skriv [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Returnerar:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Returnerar eller anger statusen för kommentaren. Läs/skriv [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |