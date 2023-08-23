---
title: IModernComment
second_title: Aspose.Slides for Java API Reference
description: Represents a comment on a slide.
type: docs
url: /com.aspose.slides/imoderncomment/
---
**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Represents a comment on a slide.

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
## Methods

| Method | Description |
| --- | --- |
| [getShape()](#getShape--) | Returns a shape associated with the comment. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Returns or sets starting position of text selection in text frame if the comment associated with AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Returns or sets starting position of text selection in text frame if the comment associated with AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Returns or sets text selection length in text frame if the comment associated with AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Returns or sets text selection length in text frame if the comment associated with AutoShape. |
| [getStatus()](#getStatus--) | Returns or sets the status of the comment. |
| [setStatus(byte value)](#setStatus-byte-) | Returns or sets the status of the comment. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Returns a shape associated with the comment. Read-only [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Returns or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int.

**Returns:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Returns or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Returns or sets text selection length in text frame if the comment associated with AutoShape. Read/write int.

**Returns:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Returns or sets text selection length in text frame if the comment associated with AutoShape. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Returns or sets the status of the comment. Read/write [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Returns:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Returns or sets the status of the comment. Read/write [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

