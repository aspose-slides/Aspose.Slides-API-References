---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Text style formatting properties.
type: docs
url: /hu/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Szövegstílus formázási tulajdonságok.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Ha a stílus szintje létezik, visszaadja, egyébként null értéket ad vissza. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Alapértelmezett bekezdés tulajdonságai. |
| [getEffective()](#getEffective--) | Lekéri a hatékony szövegstílus formázási adatokat az öröklődés alkalmazásával. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Ha a stílus szintje létezik, visszaadja, egyébként null értéket ad vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A szint nulla alapú indexe. 0..8 intervallumban kell legyen. |

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - A [IParagraphFormat](../../com.aspose.slides/iparagraphformat) szint formázása.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Alapértelmezett bekezdés tulajdonságai. Csak olvasható [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Lekéri a hatékony szövegstílus formázási adatokat az öröklődés alkalmazásával.

**Visszatér:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Egy [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).