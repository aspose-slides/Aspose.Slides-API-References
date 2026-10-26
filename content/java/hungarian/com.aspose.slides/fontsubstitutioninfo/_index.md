---
title: FontSubstitutionInfo
second_title: Aspose.Slides Java API referencia
description: Ez a struktúra a betűtípus helyettesítésével kapcsolatos információkat tartalmazza, amikor megjelenik.
type: docs
url: /hu/com.aspose.slides/fontsubstitutioninfo/
---
**Öröklés:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Ez a struktúra a betűtípus helyettesítéssel kapcsolatos információkat képviseli, amikor megjelenik.

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
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Létrehozza a [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) osztály egy példányát. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Jelzi a forrás betűtípus nevét a prezentációban. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Jelzi az eredeti betűtípus helyettesítő betűtípus nevét. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Létrehozza a [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) osztály egy példányát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| originFontName | java.lang.String | A forrás betűtípus neve a prezentációban String |
| substFontName | java.lang.String | Az eredeti betűtípus helyettesítő betűtípus neve String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Jelzi a forrás betűtípus nevét a prezentációban. Csak olvasható String

**Visszatér:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Jelzi az eredeti betűtípus helyettesítő betűtípus nevét. Csak olvasható String

**Visszatér:**
java.lang.String