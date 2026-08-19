---
title: IModernComment
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje komentář na snímku.
type: docs
url: /cs/com.aspose.slides/imoderncomment/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Reprezentuje komentář na snímku.

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
## Metody

| Metoda | Popis |
| --- | --- |
| [getShape()](#getShape--) | Vrací tvar spojený s komentářem. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Vrací nebo nastavuje počáteční pozici výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Vrací nebo nastavuje počáteční pozici výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Vrací nebo nastavuje délku výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Vrací nebo nastavuje délku výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. |
| [getStatus()](#getStatus--) | Vrací nebo nastavuje stav komentáře. |
| [setStatus(byte value)](#setStatus-byte-) | Vrací nebo nastavuje stav komentáře. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

Vrací tvar spojený s komentářem. Pouze pro čtení [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

Vrací nebo nastavuje počáteční pozici výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. Čtení/Zápis int.

**Vrací:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

Vrací nebo nastavuje počáteční pozici výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

Vrací nebo nastavuje délku výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. Čtení/Zápis int.

**Vrací:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

Vrací nebo nastavuje délku výběru textu v textovém rámci, pokud je komentář spojen s AutoShape. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

Vrací nebo nastavuje stav komentáře. Čtení/Zápis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Vrací:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

Vrací nebo nastavuje stav komentáře. Čtení/Zápis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |