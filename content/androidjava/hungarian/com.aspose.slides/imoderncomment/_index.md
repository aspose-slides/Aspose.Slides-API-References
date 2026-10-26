---
title: IModernComment
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: Egy dián lévő megjegyzést reprezentál.
type: docs
url: /hu/com.aspose.slides/imoderncomment/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Egy dián lévő megjegyzést reprezentál.

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

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShape()](#getShape--) | Visszaad egy shape-et, amely a megjegyzéshez tartozik. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Visszaadja vagy beállítja a szövegrész kezdeti pozícióját a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Visszaadja vagy beállítja a szövegrész kezdeti pozícióját a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Visszaadja vagy beállítja a szövegrész hosszát a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Visszaadja vagy beállítja a szövegrész hosszát a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. |
| [getStatus()](#getStatus--) | Visszaadja vagy beállítja a megjegyzés állapotát. |
| [setStatus(byte value)](#setStatus-byte-) | Visszaadja vagy beállítja a megjegyzés állapotát. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Visszaad egy shape-et, amely a megjegyzéshez tartozik. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Visszaadja vagy beállítja a szövegrész kezdeti pozícióját a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. Olvasás/írás int.

**Visszatér:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Visszaadja vagy beállítja a szövegrész kezdeti pozícióját a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Visszaadja vagy beállítja a szövegrész hosszát a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. Olvasás/írás int.

**Visszatér:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Visszaadja vagy beállítja a szövegrész hosszát a text frame-ben, ha a megjegyzés AutoShape-hez tartozik. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Visszaadja vagy beállítja a megjegyzés állapotát. Olvasás/írás [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Visszatér:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Visszaadja vagy beállítja a megjegyzés állapotát. Olvasás/írás [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |