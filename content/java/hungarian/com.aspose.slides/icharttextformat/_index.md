---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: Chart operate with restricted set of text format properties.
type: docs
url: /hu/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

A diagram korlátozott szövegformátum tulajdonságokkal működik. Az IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfészek leírják ezt a korlátozott halmazt.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Visszaadja a diagram szöveg elemeinek formátumát. |
| [getParagraphFormat()](#getParagraphFormat--) | Visszaadja a bekezdés formátumát. |
| [getPortionFormat()](#getPortionFormat--) | Visszaadja a részletformátumot. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Másolja a szövegformátumot a megadott szövegkeretbe. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Másolja a szövegformátumot a megadott szövegkeretből. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Visszaadja a diagram szöveg elemeinek formátumát. Csak olvasható [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

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

Visszaadja a részletformátumot. Csak olvasható [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Visszatér:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Másolja a szövegformátumot a megadott szövegkeretbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Szövegkeret, amibe a szövegformátum másolása. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Másolja a szövegformátumot a megadott szövegkeretből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Szövegkeret, ahonnan a szövegformátum másolása. |