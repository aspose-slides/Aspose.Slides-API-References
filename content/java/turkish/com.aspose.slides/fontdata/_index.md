---
title: FontData
second_title: Aspose.Slides için Java API Referansı
description: Bir yazı tipi tanımını temsil eder.
type: docs
url: /tr/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Represents a font definition. Immutable.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
## Yöntemler

| Yöntem | Açıklama |
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

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Font name. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Returns the font name. Read/write String.

**Döndürür:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


Returns the font name, replacing theme referrence with an actual font used.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Theme from which themed font name should be taken. Its up to caller to provide a correct value. See [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Döndürür:**
java.lang.String - Font name.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether two FontData instances are equal.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | The FontData to compare with the current FontData. |

**Döndürür:**
boolean - **true** if the specified FontData is equal to the current FontData; otherwise, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Döndürür:**
int - Hash code of the FontData.
### toString() {#toString--}
```
public String toString()
```


Returns string representation.

**Döndürür:**
java.lang.String - String representatoin.