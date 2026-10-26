---
title: FontSubstitutionInfo
second_title: Aspose.Slides für Java API Referenz
description: Diese Struktur stellt die Informationen zur Schriftart-Ersetzung dar, wenn sie gerendert wird.
type: docs
url: /de/com.aspose.slides/fontsubstitutioninfo/
---
**Inheritance:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Diese Struktur stellt die Informationen zur Schriftart-Ersetzung dar, wenn sie gerendert wird.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Erstellt eine Instanz der Klasse [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Gibt den Quell-Schriftartnamen in der Präsentation an. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Gibt den Ersetzungs-Schriftartnamen für die Originalschriftart an. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Erstellt eine Instanz der Klasse [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| originFontName | java.lang.String | Quell-Schriftartname in der Präsentation String |
| substFontName | java.lang.String | Ersetzungs-Schriftartname für die Originalschriftart String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Gibt den Quell-Schriftartnamen in der Präsentation an. Nur lesbarer String

**Rückgabe:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Gibt den Ersetzungs-Schriftartnamen für die Originalschriftart an. Nur lesbarer String

**Rückgabe:**
java.lang.String