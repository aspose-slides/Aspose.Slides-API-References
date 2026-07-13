---
title: ModernComment
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een opmerking op een dia.
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

Vertegenwoordigt een opmerking op een dia.

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

| Methode | Beschrijving |
| --- | --- |
| [getShape()](#getShape--) | Retourneert een shape die bij de opmerking hoort. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Haalt of stelt de startpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Haalt of stelt de startpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Haalt of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Haalt of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. |
| [getStatus()](#getStatus--) | Haalt of stelt de status van de opmerking. |
| [setStatus(byte value)](#setStatus-byte-) | Haalt of stelt de status van de opmerking. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Retourneert een shape die bij de opmerking hoort. Alleen-lezen [IShape](../../com.aspose.slides/ishape).

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Haalt of stelt de startpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. Lezen/Schrijven int.

**Retourneert:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Haalt of stelt de startpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Haalt of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. Lezen/Schrijven int.

**Retourneert:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Haalt of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan een AutoShape. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Haalt of stelt de status van de opmerking. Lezen/Schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Retourneert:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Haalt of stelt de status van de opmerking. Lezen/Schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert een Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject