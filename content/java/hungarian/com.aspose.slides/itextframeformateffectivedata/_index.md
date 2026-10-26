---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Változtathatatlan objektum, amely hatékony szövegkeret formázási tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Változtathatatlan objektum, amely hatékony szövegkeret formázási tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [ITextFrameFormat](../../com.aspose.slides/itextframeformat) interfésszel együtt használható a hatékony formázási értékek visszaadására, öröklődéssel alkalmazva.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Visszaadja a hatékony szöveg stílusát. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja a bal margót (pontban) egy TextFrame-ben. |
| [getMarginRight()](#getMarginRight--) | Visszaadja a jobb margót (pontban) egy TextFrame-ben. |
| [getMarginTop()](#getMarginTop--) | Visszaadja a felső margót (pontban) egy TextFrame-ben. |
| [getMarginBottom()](#getMarginBottom--) | Visszaadja az alsó margót (pontban) egy TextFrame-ben. |
| [getWrapText()](#getWrapText--) | Visszaadja, hogy a szöveg van-e tördelve a TextFrame margóin. |
| [getAnchoringType()](#getAnchoringType--) | Visszaadja a függőleges horgonyszöveget egy TextFrame-ben. |
| [getCenterText()](#getCenterText--) | Visszaadja, hogy a szöveget vízszintesen középre kell-e helyezni a dobozban. |
| [getTextVerticalType()](#getTextVerticalType--) | Visszaadja a szöveg tájolását. |
| [getAutofitType()](#getAutofitType--) | Visszaadja a szöveg automatikus illesztés módját. |
| [getColumnCount()](#getColumnCount--) | Megadja a szöveg oszlopainak számát a határoló téglalapban. |
| [getColumnSpacing()](#getColumnSpacing--) | Megadja a szöveg oszlopok közötti távolságot a szövegterületen (pontban). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Visszaadja a hatékony szöveg stílusát. Csak olvasható [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Visszatér:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Visszaadja a bal margót (pontban) egy TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Visszaadja a jobb margót (pontban) egy TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Visszaadja a felső margót (pontban) egy TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Visszaadja az alsó margót (pontban) egy TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Visszaadja, hogy a szöveg van-e tördelve a TextFrame margóin. Csak olvasható boolean.

**Visszatér:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Visszaadja a függőleges horgonyszöveget egy TextFrame-ben. Csak olvasható [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Visszaadja, hogy a szöveget vízszintesen középre kell-e helyezni a dobozban. Csak olvasható boolean.

**Visszatér:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Visszaadja a szöveg tájolását. Csak olvasható [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatér:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Visszaadja a szöveg automatikus illesztés módját. Csak olvasható [TextAutofitType](../../com.aspose.slides/textautofittype).

**Visszatér:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Megadja a szöveg oszlopainak számát a határoló téglalapban. Csak olvasható int.

**Visszatér:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Megadja a szöveg oszlopok közötti távolságot a szövegterületen (pontban). Csak olvasható float.

**Visszatér:**
float