---
title: IModernComment
second_title: Aspose.Slides voor Android via Java API-referentie
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
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShape()](#getShape--) | Retourneert een shape die aan de opmerking is gekoppeld. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Retourneert of stelt de startpositie van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Retourneert of stelt de startpositie van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Retourneert of stelt de lengte van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Retourneert of stelt de lengte van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. |
| [getStatus()](#getStatus--) | Retourneert of stelt de status van de opmerking in. |
| [setStatus(byte value)](#setStatus-byte-) | Retourneert of stelt de status van de opmerking in. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Retourneert een shape die aan de opmerking is gekoppeld. Alleen lezen [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Retourneert of stelt de startpositie van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. Lezen/Schrijven int.

**Retour:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Retourneert of stelt de startpositie van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Retourneert of stelt de lengte van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. Lezen/Schrijven int.

**Retour:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Retourneert of stelt de lengte van de tekstreek in het tekstframe in als de opmerking gekoppeld is aan AutoShape. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Retourneert of stelt de status van de opmerking in. Lezen/Schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Retour:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Retourneert of stelt de status van de opmerking in. Lezen/Schrijven [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |