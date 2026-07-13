---
title: ModernComment
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Reprezentuje komentář na snímku.
type: docs
url: /cs/com.aspose.slides/moderncomment/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Reprezentuje komentář na snímku.

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
## Metody

| Metoda | Popis |
| --- | --- |
| [getShape()](#getShape--) | Vrací tvar spojený s komentářem. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Získává nebo nastavuje počáteční pozici výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Získává nebo nastavuje počáteční pozici výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Získává nebo nastavuje délku výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Získává nebo nastavuje délku výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. |
| [getStatus()](#getStatus--) | Získává nebo nastavuje stav komentáře. |
| [setStatus(byte value)](#setStatus-byte-) | Získává nebo nastavuje stav komentáře. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Vrací tvar spojený s komentářem. Pouze pro čtení [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Získává nebo nastavuje počáteční pozici výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. Čtení/zápis int.

**Vrací:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Získává nebo nastavuje počáteční pozici výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Získává nebo nastavuje délku výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. Čtení/zápis int.

**Vrací:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Získává nebo nastavuje délku výběru textu v textovém rámečku, pokud je komentář spojen s AutoShape. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Získává nebo nastavuje stav komentáře. Čtení/zápis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Vrací:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Získává nebo nastavuje stav komentáře. Čtení/zápis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject