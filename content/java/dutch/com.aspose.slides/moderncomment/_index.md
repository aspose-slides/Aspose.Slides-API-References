---
title: ModernComment
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een opmerking op een dia voor.
type: docs
url: /nl/com.aspose.slides/moderncomment/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Stelt een opmerking op een dia voor.

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

| Methode | Beschrijving |
| --- | --- |
| [getShape()](#getShape--) | Retourneert een vorm die aan de opmerking is gekoppeld. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Haalt of stelt de startpositie van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Haalt of stelt de startpositie van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Haalt of stelt de lengte van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Haalt of stelt de lengte van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. |
| [getStatus()](#getStatus--) | Haalt of stelt de status van de opmerking in. |
| [setStatus(byte value)](#setStatus-byte-) | Haalt of stelt de status van de opmerking in. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Retourneert een vorm die aan de opmerking is gekoppeld. Alleen-lezen [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Haalt of stelt de startpositie van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. Lezen/schrijven int.

**Retour:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Haalt of stelt de startpositie van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Haalt of stelt de lengte van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. Lezen/schrijven int.

**Retour:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Haalt of stelt de lengte van de tekstselectie in het tekstvak in als de opmerking gekoppeld is aan AutoShape. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Haalt of stelt de status van de opmerking in. Lezen/schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Retour:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Haalt of stelt de status van de opmerking in. Lezen/schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject