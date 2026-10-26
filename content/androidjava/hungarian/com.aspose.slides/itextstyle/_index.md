---
title: ITextStyle
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: Szövegstílus formázási tulajdonságok.
type: docs
url: /hu/com.aspose.slides/itextstyle/
---``` 
public interface ITextStyle
```

Szövegstílus formázási tulajdonságok.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Ha a stílus szintje létezik, visszaadja, egyébként null-t ad vissza. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Alapértelmezett bekezdés tulajdonságai. |
| [getEffective()](#getEffective--) | Megkapja a hatékony szövegstílus formázási adatokat az öröklődés alkalmazásával. |
### getLevel(int index) {#getLevel-int-}
``` 
public abstract IParagraphFormat getLevel(int index)
```

Ha a stílus szintje létezik, visszaadja, egyébként null-t ad vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A szint nullalapú indexe. 0..8 intervallumban kell legyen. |

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - [IParagraphFormat](../../com.aspose.slides/iparagraphformat) szint formázása.
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

Megkapja a hatékony szövegstílus formázási adatokat az öröklődés alkalmazásával.

**Visszatér:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - egy [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).