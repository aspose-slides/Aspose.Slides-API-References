---
title: IOverridableText
second_title: Aspose.Slides Java API referencia
description: Ábrához felülírható szöveget képvisel.
type: docs
url: /hu/com.aspose.slides/ioverridabletext/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Ábrához felülírható szöveget képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Tárgya egy gazdag formázott szöveg lehet. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializálja a TextFrameForOverriding-ot a "text" paraméterben megadott szöveggel. |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Tárgya egy gazdag formázott szöveg lehet. Ha ez a tulajdonság nem null, akkor ez a formázott szövegérték felülírja az automatikusan generált szöveget. Az automatikusan generált szöveg egy implicit tulajdonságja az adatcímkének, a megjelenítő egység címkének az értéktengelyen, a tengelycímnek, az ábra címének, valamint a trendvonal címkének. Az automatikusan generált szöveget az IFormattedTextContainer.TextFormat tulajdonsággal formázzák. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Inicializálja a TextFrameForOverriding-ot a "text" paraméterben megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Szöveg egy új TextFrameForOverriding számára. |

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe) - Szövegkeret [ITextFrame](../../com.aspose.slides/itextframe)