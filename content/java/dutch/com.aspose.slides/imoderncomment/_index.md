---
title: IModernComment
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een opmerking op een dia voor.
type: docs
url: /nl/com.aspose.slides/imoderncomment/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
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
| [getShape()](#getShape--) | Retourneert een shape die bij de opmerking hoort. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Retourneert of stelt de beginpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Retourneert of stelt de beginpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Retourneert of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Retourneert of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. |
| [getStatus()](#getStatus--) | Retourneert of stelt de status van de opmerking in. |
| [setStatus(byte value)](#setStatus-byte-) | Retourneert of stelt de status van de opmerking in. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Retourneert een shape die bij de opmerking hoort. Alleen-lezen [IShape](../../com.aspose.slides/ishape).

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Retourneert of stelt de beginpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. Lezen/schrijven int.

**Retourneert:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Retourneert of stelt de beginpositie van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Retourneert of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. Lezen/schrijven int.

**Retourneert:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Retourneert of stelt de lengte van de tekstselectie in het tekstframe in als de opmerking is gekoppeld aan AutoShape. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Retourneert of stelt de status van de opmerking in. Lezen/schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Retourneert:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Retourneert of stelt de status van de opmerking in. Lezen/schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |