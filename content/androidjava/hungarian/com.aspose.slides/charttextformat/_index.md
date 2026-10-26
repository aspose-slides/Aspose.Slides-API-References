---
title: ChartTextFormat
second_title: Aspose.Slides for Android a Java API hivatkozása
description: Alapértelmezett szövegformázást határoz meg a diagram szövegelemekhez.
type: docs
url: /hu/com.aspose.slides/charttextformat/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Specifies default text formatting for chart text elements.
## Módszerek

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Másolja a szövegformátumot a megadott szövegkeretbe. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Másolja a szövegformátumot a megadott szövegkeretből. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```

TextBlockFormat. Csak olvasható [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Visszatérési érték:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. Csak olvasható [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Visszatérési érték:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. Csak olvasható [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Visszatérési érték:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

Másolja a szövegformátumot a megadott szövegkeretbe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Szövegkeret, amelybe a szövegformátumot másolni kell. |
### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

Másolja a szövegformátumot a megadott szövegkeretből.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Szövegkeret, amelyből a szövegformátumot másolni kell. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject