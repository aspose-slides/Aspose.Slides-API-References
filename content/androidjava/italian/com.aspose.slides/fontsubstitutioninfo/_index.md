---
title: FontSubstitutionInfo
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Questa struttura rappresenta le informazioni sulla sostituzione del font quando verrà renderizzata.
type: docs
url: /it/com.aspose.slides/fontsubstitutioninfo/
---
**Eredità:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Questa struttura rappresenta le informazioni sulla sostituzione del font quando verrà renderizzata.

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Crea un'istanza della classe [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Indica il nome del font sorgente nella presentazione. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indica il nome del font di sostituzione per il font originale. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Crea un'istanza della classe [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originFontName | java.lang.String | Nome del font sorgente nella presentazione String |
| substFontName | java.lang.String | Nome del font di sostituzione per il font originale String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Indica il nome del font sorgente nella presentazione. String sola lettura

**Restituisce:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Indica il nome del font di sostituzione per il font originale. String sola lettura

**Restituisce:**
java.lang.String