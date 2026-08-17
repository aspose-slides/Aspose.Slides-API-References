---
title: FontData
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une définition de police.
type: docs
url: /fr/com.aspose.slides/fontdata/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Represents a font definition. Immuable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
## Méthodes

| Méthode | Description |
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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font name. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Returns the font name. Lecture/écriture String.

**Renvoie:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


Returns the font name, replacing theme referrence with an actual font used.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Theme from which themed font name should be taken. Its up to caller to provide a correct value. See [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Renvoie:**
java.lang.String - Font name.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether two FontData instances are equal.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The FontData to compare with the current FontData. |

**Renvoie:**
boolean - **true** if the specified FontData is equal to the current FontData; otherwise, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Renvoie:**
int - Hash code of the FontData.
### toString() {#toString--}
```
public String toString()
```


Returns string representation.

**Renvoie:**
java.lang.String - String representatoin.