---
title: ModernComment
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en kommentar på en bild.
type: docs
url: /sv/com.aspose.slides/moderncomment/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Representerar en kommentar på en bild.

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShape()](#getShape--) | Returnerar en shape som är associerad med kommentaren. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Hämtar eller anger startposition för textmarkering i textramen om kommentaren är associerad med AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Hämtar eller anger startposition för textmarkering i textramen om kommentaren är associerad med AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Hämtar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Hämtar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med AutoShape. |
| [getStatus()](#getStatus--) | Hämtar eller anger status för kommentaren. |
| [setStatus(byte value)](#setStatus-byte-) | Hämtar eller anger status för kommentaren. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Returnerar en shape som är associerad med kommentaren. Skrivskyddad [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Hämtar eller anger startposition för textmarkering i textramen om kommentaren är associerad med AutoShape. Läs/skriv int.

**Returnerar:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Hämtar eller anger startposition för textmarkering i textramen om kommentaren är associerad med AutoShape. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Hämtar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med AutoShape. Läs/skriv int.

**Returnerar:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Hämtar eller anger längden på textmarkeringen i textramen om kommentaren är associerad med AutoShape. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Hämtar eller anger status för kommentaren. Läs/skriv [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Returnerar:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Hämtar eller anger status för kommentaren. Läs/skriv [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject