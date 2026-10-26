---
title: FontSubstitutionInfo
second_title: Referencia de la API de Aspose.Slides para Java
description: Esta estructura representa la información sobre la sustitución de fuentes cuando se renderice.
type: docs
url: /es/com.aspose.slides/fontsubstitutioninfo/
---
**Herencia:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Esta estructura representa la información sobre la sustitución de fuentes cuando se renderice.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Crea una instancia de la clase [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Indica el nombre de la fuente origen en la presentación. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indica el nombre de la fuente de sustitución para la fuente original. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Crea una instancia de la clase [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| originFontName | java.lang.String | Nombre de fuente origen en la presentación String |
| substFontName | java.lang.String | Nombre de fuente de sustitución para la fuente original String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Indica el nombre de la fuente origen en la presentación. Sólo lectura String

**Devuelve:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Indica el nombre de la fuente de sustitución para la fuente original. Sólo lectura String

**Devuelve:**
java.lang.String