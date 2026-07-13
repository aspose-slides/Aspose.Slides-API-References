---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Represent shapes style reference.
type: docs
url: /sv/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Representerar formens stilreferens.
## Metoder

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Returnerar en formens konturfärg. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Returnerar eller anger linjens kolumnindex i en stilmatris. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Returnerar eller anger linjens kolumnindex i en stilmatris. |
| [getFillColor()](#getFillColor--) | Returnerar en formens fyllningsfärg. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Returnerar eller anger formens fyllningskolumnindex i stilmatriser. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Returnerar eller anger formens fyllningskolumnindex i stilmatriser. |
| [getEffectColor()](#getEffectColor--) | Returnerar en formens effektfärg. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Returnerar eller anger formens effektkolumnindex i en stilmatris. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Returnerar eller anger formens effektkolumnindex i en stilmatris. |
| [getFontColor()](#getFontColor--) | Returnerar en formens teckensnittsfärg. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Returnerar eller anger formens teckensnittsindex i en teckensnittssamling. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Returnerar eller anger formens teckensnittsindex i en teckensnittssamling. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


Returnerar en formens konturfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


Returnerar eller anger linjens kolumnindex i en stilmatris. Läs/skriv int.

**Returnerar:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


Returnerar eller anger linjens kolumnindex i en stilmatris. Läs/skriv int.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


Returnerar en formens fyllningsfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


Returnerar eller anger formens fyllningskolumnindex i stilmatriser. 0 betyder ingen fyllning, positivt värde – index i temats fyllningsstilar, negativt värde – index i temats bakgrundsstilar. Läs/skriv short.

**Returnerar:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


Returnerar eller anger formens fyllningskolumnindex i stilmatriser. 0 betyder ingen fyllning, positivt värde – index i temats fyllningsstilar, negativt värde – index i temats bakgrundsstilar. Läs/skriv short.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


Returnerar en formens effektfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


Returnerar eller anger formens effektkolumnindex i en stilmatris. Läs/skriv long.

**Returnerar:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


Returnerar eller anger formens effektkolumnindex i en stilmatris. Läs/skriv long.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


Returnerar en formens teckensnittsfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


Returnerar eller anger formens teckensnittsindex i en teckensnittssamling. Läs/skriv [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Returnerar:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


Returnerar eller anger formens teckensnittsindex i en teckensnittssamling. Läs/skriv [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |