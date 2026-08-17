---
title: FontSubstitutionInfo
second_title: Référence de l'API Aspose.Slides pour Java
description: Cette structure représente les informations sur le remplacement de police lorsqu’elle sera rendue.
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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Crée une instance de la classe [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Indique le nom de police source dans la présentation. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indique le nom de police de remplacement pour la police d'origine. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Crée une instance de la classe [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| originFontName | java.lang.String | Nom de police source dans la présentation String |
| substFontName | java.lang.String | Nom de police de remplacement pour la police d'origine String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Indique le nom de police source dans la présentation. Lecture seule String

**Retour :**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Indique le nom de police de remplacement pour la police d'origine. Lecture seule String

**Retour :**
java.lang.String