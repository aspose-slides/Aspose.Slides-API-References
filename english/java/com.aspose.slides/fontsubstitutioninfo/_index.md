---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Java API Reference
description: This structure represents the information about the font replacement when it will be rendered.
type: docs
weight: 212
url: /java/com.aspose.slides/fontsubstitutioninfo/
---
**Inheritance:**
java.lang.Object
```
public class FontSubstitutionInfo
```

This structure represents the information about the font replacement when it will be rendered.

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
```


Indicates the replacement font name for the original font. Read-only String

**Returns:**
java.lang.String
