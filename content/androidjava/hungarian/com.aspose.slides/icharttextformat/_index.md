---
title: IChartTextFormat
second_title: Aspose.Slides Androidra a Java API hivatkozáson keresztül
description: A Chart korlátozott szövegformázási tulajdonságok halmazával működik.
type: docs
url: /hu/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

A Chart korlátozott szövegformázási tulajdonságok halmazával működik. Az IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat és IChartPortionFormat interfészek leírják ezt a korlátozott halmazt.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Visszaadja a diagram szövegelemek formátumát. |
| [getParagraphFormat()](#getParagraphFormat--) | Visszaadja a bekezdés formátumát. |
| [getPortionFormat()](#getPortionFormat--) | Visszaadja a részlet formátumát. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | A szövegformátumot a megadott szövegkeretbe másolja. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | A szövegformátumot a megadott szövegkeretből másolja. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Visszaadja a diagram szövegelemek formátumát. Csak olvasható [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Visszatér:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Visszaadja a bekezdés formátumát. Csak olvasható [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Visszatér:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Visszaadja a részlet formátumát. Csak olvasható [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Visszatér:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

A szövegformátumot a megadott szövegkeretbe másolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Szövegkeret, ahová a szövegformátumot másolja. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

A szövegformátumot a megadott szövegkeretből másolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Szövegkeret, amelyből a szövegformátumot másolja. |