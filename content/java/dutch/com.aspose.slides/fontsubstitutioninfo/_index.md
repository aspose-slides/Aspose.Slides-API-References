---
title: FontSubstitutionInfo
second_title: Aspose.Slides voor Java API-referentie
description: Deze structuur vertegenwoordigt de informatie over de lettertypevervanging wanneer deze wordt gerenderd.
type: docs
url: /nl/com.aspose.slides/fontsubstitutioninfo/
---
**Inheritance:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Deze structuur vertegenwoordigt de informatie over de lettertypevervanging wanneer deze wordt gerenderd.

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
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Maakt een instantie van [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) klasse aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Geeft de naam van het bronlettertype in de presentatie aan. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Geeft de vervangende lettertype-naam voor het oorspronkelijke lettertype aan. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Maakt een instantie van [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) klasse aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| originFontName | java.lang.String | Bronlettertype naam in presentatie String |
| substFontName | java.lang.String | Vervangend lettertype naam voor het oorspronkelijke lettertype String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Geeft de naam van het bronlettertype in de presentatie aan. Alleen-lezen String

**Retour:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Geeft de vervangende lettertype-naam voor het oorspronkelijke lettertype aan. Alleen-lezen String

**Retour:**
java.lang.String