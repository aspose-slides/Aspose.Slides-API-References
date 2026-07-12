---
title: FontSubstitutionInfo
second_title: Aspose.Slides Androidra a Java API referenciával
description: Ez a struktúra a betűtípus helyettesítésének információit tartalmazza, amikor megjelenik.
type: docs
url: /hu/com.aspose.slides/fontsubstitutioninfo/
---
**Öröklés:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Ez a struktúra a betűtípus helyettesítésének információit tartalmazza, amikor megjelenik.

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
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Létrehoz egy példányt a [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | A prezentációban a forrás betűtípus nevét jelzi. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Az eredeti betűtípus helyettesítő betűtípus nevét jelzi. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Létrehoz egy példányt a [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) osztályból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| originFontName | java.lang.String | A prezentációban a forrás betűtípus neve String |
| substFontName | java.lang.String | Az eredeti betűtípus helyettesítő betűtípus neve String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


A prezentációban a forrás betűtípus nevét jelzi. Csak olvasható String

**Visszatérési érték:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Az eredeti betűtípus helyettesítő betűtípus nevét jelzi. Csak olvasható String

**Visszatérési érték:**
java.lang.String