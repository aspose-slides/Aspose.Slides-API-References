---
title: ITextStyleEffectiveData
second_title: Aspose.Slides Java API Referencia
description: Immutable objektum, amely a hatékony szövegstílus tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Immutable objektum, amely a hatékony szövegstílus tulajdonságait tartalmazza.

--------------------

Ez az interfész a [ITextStyle](../../com.aspose.slides/itextstyle) interfésszel együtt használható a hatékony formázási értékek visszaadásához, öröklődés alkalmazásával.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Visszaadja a hatékony stílus szintjét. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Visszaadja a hatékony alapértelmezett bekezdés tulajdonságait. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Visszaadja a hatékony stílus szintjét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A szint nulla-bázisú indexe. 0..8 intervallumban kell lennie. |

**Visszatérési érték:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A(z) [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) szint hatékony formázása.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Visszaadja a hatékony alapértelmezett bekezdés tulajdonságait. Írásvédett [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Visszatérési érték:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)