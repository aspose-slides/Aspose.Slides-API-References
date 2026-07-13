---
title: FontSubstitutionInfo
second_title: Aspose.Slides voor Android via Java API-referentie
description: Deze structuur vertegenwoordigt de informatie over de vervanging van het lettertype wanneer het wordt gerenderd.
type: docs
url: /nl/com.aspose.slides/fontsubstitutioninfo/
---
**Overerving:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Deze structuur vertegenwoordigt de informatie over het vervangen van het lettertype wanneer het wordt gerenderd.

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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Maakt een exemplaar van de [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) klasse. |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Geeft de bronlettertype-naam in de presentatie weer. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Geeft de vervangende lettertype-naam voor het originele lettertype weer. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Maakt een exemplaar van de [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| originFontName | java.lang.String | Bronlettertype-naam in presentatie String |
| substFontName | java.lang.String | Vervangende lettertype-naam voor het originele lettertype String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Geeft de bronlettertype-naam in de presentatie weer. Alleen-lezen String

**Retourwaarde:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Geeft de vervangende lettertype-naam voor het originele lettertype weer. Alleen-lezen String

**Retourwaarde:**
java.lang.String