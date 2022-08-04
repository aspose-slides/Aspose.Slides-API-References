---
title: FontData
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a font definition.
type: docs
weight: 201
url: /java/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Represents a font definition. Immutable.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
| [FontData(String fontName, byte charSet)](#FontData-java.lang.String-byte-) |  |
| [FontData(String fontName, byte charSet, byte pitchFamily)](#FontData-java.lang.String-byte-byte-) |  |
| [FontData(String fontName, byte charSet, byte pitchFamily, int fontStyle, byte[] panose)](#FontData-java.lang.String-byte-byte-int-byte---) |  |
| [FontData(FontData fontData)](#FontData-com.aspose.slides.FontData-) |  |
| [FontData(FontData fontData, String fontName)](#FontData-com.aspose.slides.FontData-java.lang.String-) |  |
| [FontData(FontData fontData, String fontName, byte charSet)](#FontData-com.aspose.slides.FontData-java.lang.String-byte-) |  |
| [FontData(FontData fontData, int fontStyle)](#FontData-com.aspose.slides.FontData-int-) |  |
| [FontData(FontData fontData, String fontName, byte charSet, byte pitchFamily)](#FontData-com.aspose.slides.FontData-java.lang.String-byte-byte-) |  |
| [FontData(String fontName, FontEntityAtom fatom)](#FontData-java.lang.String-com.aspose.slides.pptbinaryfile.FontEntityAtom-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Returns the font name. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returns the font name, replacing theme referrence with an actual font used. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether two FontData instances are equal. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [toString()](#toString--) | Returns string representation. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```


Creates a new FontData object with the specified font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font name. |

### FontData(String fontName, byte charSet) {#FontData-java.lang.String-byte-}
```
 FontData(String fontName, byte charSet)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |
| charSet | byte |  |

### FontData(String fontName, byte charSet, byte pitchFamily) {#FontData-java.lang.String-byte-byte-}
```
 FontData(String fontName, byte charSet, byte pitchFamily)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |
| charSet | byte |  |
| pitchFamily | byte |  |

### FontData(String fontName, byte charSet, byte pitchFamily, int fontStyle, byte[] panose) {#FontData-java.lang.String-byte-byte-int-byte---}
```
 FontData(String fontName, byte charSet, byte pitchFamily, int fontStyle, byte[] panose)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |
| charSet | byte |  |
| pitchFamily | byte |  |
| fontStyle | int |  |
| panose | byte[] |  |

### FontData(FontData fontData) {#FontData-com.aspose.slides.FontData-}
```
 FontData(FontData fontData)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [FontData](../../com.aspose.slides/fontdata) |  |

### FontData(FontData fontData, String fontName) {#FontData-com.aspose.slides.FontData-java.lang.String-}
```
 FontData(FontData fontData, String fontName)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [FontData](../../com.aspose.slides/fontdata) |  |
| fontName | java.lang.String |  |

### FontData(FontData fontData, String fontName, byte charSet) {#FontData-com.aspose.slides.FontData-java.lang.String-byte-}
```
 FontData(FontData fontData, String fontName, byte charSet)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [FontData](../../com.aspose.slides/fontdata) |  |
| fontName | java.lang.String |  |
| charSet | byte |  |

### FontData(FontData fontData, int fontStyle) {#FontData-com.aspose.slides.FontData-int-}
```
 FontData(FontData fontData, int fontStyle)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [FontData](../../com.aspose.slides/fontdata) |  |
| fontStyle | int |  |

### FontData(FontData fontData, String fontName, byte charSet, byte pitchFamily) {#FontData-com.aspose.slides.FontData-java.lang.String-byte-byte-}
```
 FontData(FontData fontData, String fontName, byte charSet, byte pitchFamily)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [FontData](../../com.aspose.slides/fontdata) |  |
| fontName | java.lang.String |  |
| charSet | byte |  |
| pitchFamily | byte |  |

### FontData(String fontName, FontEntityAtom fatom) {#FontData-java.lang.String-com.aspose.slides.pptbinaryfile.FontEntityAtom-}
```
 FontData(String fontName, FontEntityAtom fatom)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |
| fatom | com.aspose.slides.pptbinaryfile.FontEntityAtom |  |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Returns the font name. Read/write String.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


Returns the font name, replacing theme referrence with an actual font used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Theme from which themed font name should be taken. Its up to caller to provide a correct value. See [IThemeable\#createThemeEffective](../com.aspose.slides/ithemeable\#createThemeEffective) |

**Returns:**
java.lang.String - Font name.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether two FontData instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The FontData to compare with the current FontData. |

**Returns:**
boolean - <b>true</b> if the specified FontData is equal to the current FontData; otherwise, <b>false</b>.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Returns:**
int - Hash code of the FontData.
### toString() {#toString--}
```
public String toString()
```


Returns string representation.

**Returns:**
java.lang.String - String representatoin.
