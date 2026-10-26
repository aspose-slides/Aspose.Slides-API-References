---
title: IOverridableText
second_title: Aspose.Slides Androidhoz a Java API-referencia alapján
description: A diagram számára felülírható szöveget képviseli.
type: docs
url: /hu/com.aspose.slides/ioverridabletext/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Egy diagram számára felülírható szöveget képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Tartalmazhat gazdag formázott szöveget. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializálja a TextFrameForOverriding-et a paraméterben megadott „text” szöveggel. |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveges érték felülírja az automatikusan generált szöveget. Az automatikusan generált szöveg a data label, a value axis megjelenítési egység címkéje, a tengely címe, a diagram címe, a trendvonal címkéje implicit tulajdonsága. Az automatikusan generált szöveget az IFormattedTextContainer.TextFormat tulajdonsággal formázzák. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Inicializálja a TextFrameForOverriding-et a paraméterben megadott „text” szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szöveget.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Új TextFrameForOverriding szövege. |

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe) – Szövegkeret [ITextFrame](../../com.aspose.slides/itextframe)