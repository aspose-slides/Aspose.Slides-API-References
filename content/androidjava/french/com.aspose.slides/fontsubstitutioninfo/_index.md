---
title: FontSubstitutionInfo
second_title: Aspose.Slides pour Android via la référence API Java
description: Cette structure représente les informations sur le remplacement de police lorsqu'elle sera rendue.
type: docs
url: /fr/com.aspose.slides/fontsubstitutioninfo/
---
**Héritage:**  
java.lang.Object  
```
public class FontSubstitutionInfo
```

Cette structure représente les informations sur le remplacement de police lorsqu’elle sera rendue.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Creates an instance of [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Indicates source font name in presentation. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indicates the replacement font name for the original font. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Creates an instance of [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originFontName | java.lang.String | Source font name in presentation String |
| substFontName | java.lang.String | Replacement font name for the original font String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Indicates source font name in presentation. Read-only String

**Returns:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()

Indique le nom de la police de substitution pour la police d'origine. Lecture seule String

**Renvoie:**  
java.lang.String