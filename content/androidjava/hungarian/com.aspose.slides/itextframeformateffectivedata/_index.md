---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /hu/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Megváltoztathatatlan objektum, amely a hatékony szövegkeret formázási tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [ITextFrameFormat](../../com.aspose.slides/itextframeformat) interfésszel együtt használható, hogy a öröklődéssel alkalmazott hatékony formázási értékeket adja vissza.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Visszaadja a hatékony szöveg stílusát. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja a bal margót (pontban) a TextFrame-ben. |
| [getMarginRight()](#getMarginRight--) | Visszaadja a jobb margót (pontban) a TextFrame-ben. |
| [getMarginTop()](#getMarginTop--) | Visszaadja a felső margót (pontban) a TextFrame-ben. |
| [getMarginBottom()](#getMarginBottom--) | Visszaadja az alsó margót (pontban) a TextFrame-ben. |
| [getWrapText()](#getWrapText--) | Visszaadja, hogy a szöveg meg van-e tördelve a TextFrame margóin. |
| [getAnchoringType()](#getAnchoringType--) | Visszaadja a függőleges rögzített szöveget egy TextFrame-ben. |
| [getCenterText()](#getCenterText--) | Visszaadja, hogy a szöveget vízszintesen középre kell-e helyezni a keretben. |
| [getTextVerticalType()](#getTextVerticalType--) | Visszaadja a szöveg tájolását. |
| [getAutofitType()](#getAutofitType--) | Visszaadja a szöveg automatikus illesztési módját. |
| [getColumnCount()](#getColumnCount--) | Meghatározza a szöveg oszlopainak számát a körülhatároló téglalapban. |
| [getColumnSpacing()](#getColumnSpacing--) | Meghatározza a szövegoszlopok közötti távolságot a szövegtérben (pontban). |
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


Visszaadja a bal margót (pontban) a TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Visszaadja a jobb margót (pontban) a TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Visszaadja a felső margót (pontban) a TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Visszaadja az alsó margót (pontban) a TextFrame-ben. Csak olvasható double.

**Visszatér:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Visszaadja, hogy a szöveg meg van-e tördelve a TextFrame margóin. Csak olvasható boolean.

**Visszatér:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Visszaadja a függőleges rögzített szöveget egy TextFrame-ben. Csak olvasható [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Visszaadja, hogy a szöveget vízszintesen középre kell-e helyezni a keretben. Csak olvasható boolean.

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


Visszaadja a szöveg automatikus illesztési módját. Csak olvasható [TextAutofitType](../../com.aspose.slides/textautofittype).

**Visszatér:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Meghatározza a szöveg oszlopainak számát a körülhatároló téglalapban. Csak olvasható int.

**Visszatér:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Meghatározza a szövegoszlopok közötti távolságot a szövegtérben (pontban). Csak olvasható float.

**Visszatér:**
float