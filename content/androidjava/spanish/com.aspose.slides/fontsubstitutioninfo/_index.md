---
title: FontSubstitutionInfo
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Esta estructura representa la información sobre la sustitución de fuentes cuando se renderiza.
type: docs
url: /es/com.aspose.slides/fontsubstitutioninfo/
---
**Herencia:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Esta estructura representa la información sobre la sustitución de fuentes cuando se renderiza.

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
| [getOriginalFontName()](#getOriginalFontName--) | Indica el nombre de fuente de origen en la presentación. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indica el nombre de fuente de sustitución para la fuente original. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Crea una instancia de la clase [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| originFontName | java.lang.String | Nombre de fuente de origen en la presentación String |
| substFontName | java.lang.String | Nombre de fuente de sustitución para la fuente original String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Indica el nombre de fuente de origen en la presentación. Solo lectura String

**Devuelve:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Indica el nombre de fuente de sustitución para la fuente original. Solo lectura String

**Devuelve:**
java.lang.String