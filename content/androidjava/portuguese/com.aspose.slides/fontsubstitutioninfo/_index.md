---
title: FontSubstitutionInfo
second_title: Aspose.Slides para Android via Referência da API Java
description: Esta estrutura representa as informações sobre a substituição de fonte quando for renderizada.
type: docs
url: /pt/com.aspose.slides/fontsubstitutioninfo/
---
**Herança:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Esta estrutura representa as informações sobre a substituição de fonte quando for renderizada.

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
## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Cria uma instância da classe [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Métodos

| Método | Descrição |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Indica o nome da fonte de origem na apresentação. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indica o nome da fonte de substituição para a fonte original. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Cria uma instância da classe [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| originFontName | java.lang.String | Nome da fonte de origem na apresentação String |
| substFontName | java.lang.String | Nome da fonte de substituição para a fonte original String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Indica o nome da fonte de origem na apresentação. String somente leitura

**Retorna:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Indica o nome da fonte de substituição para a fonte original. String somente leitura

**Retorna:**
java.lang.String