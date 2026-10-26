---
title: ModernComment
second_title: Aspose.Slides Java API Referencia
description: Egy diára vonatkozó megjegyzést ábrázol.
type: docs
url: /hu/com.aspose.slides/moderncomment/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Minden megvalósított interfész:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Egy diára vonatkozó megjegyzést ábrázol.

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
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getShape()](#getShape--) | Visszaad egy alakzatot, amely a megjegyzéshez tartozik. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Lekéri vagy beállítja a szövegválasztás kezdőpozícióját a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Lekéri vagy beállítja a szövegválasztás kezdőpozícióját a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Lekéri vagy beállítja a szövegválasztás hosszát a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Lekéri vagy beállítja a szövegválasztás hosszát a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. |
| [getStatus()](#getStatus--) | Lekéri vagy beállítja a megjegyzés állapotát. |
| [setStatus(byte value)](#setStatus-byte-) | Lekéri vagy beállítja a megjegyzés állapotát. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Visszaad egy alakzatot, amely a megjegyzéshez tartozik. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Lekéri vagy beállítja a szövegválasztás kezdőpozícióját a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. Olvasás/írás int.

**Visszatérési érték:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Lekéri vagy beállítja a szövegválasztás kezdőpozícióját a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Lekéri vagy beállítja a szövegválasztás hosszát a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. Olvasás/írás int.

**Visszatérési érték:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Lekéri vagy beállítja a szövegválasztás hosszát a szövegkeretben, ha a megjegyzés egy AutoShape-hez van kapcsolva. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Lekéri vagy beállítja a megjegyzés állapotát. Olvasás/írás [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Visszatérési érték:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Lekéri vagy beállítja a megjegyzés állapotát. Olvasás/írás [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject