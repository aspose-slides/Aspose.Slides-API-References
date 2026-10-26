---
title: IFontData
second_title: Aspose.Slides para Java API Reference
description: Representa uma definição de fonte.
type: docs
url: /pt/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Representa uma definição de fonte.

## Métodos

| MéTODO | DESCRIÇÃO |
| --- | --- |
| [getFontName()](#getFontName--) | Retorna o nome da fonte. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Retorna o nome da fonte, substituindo a referência do tema por uma fonte real usada. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Retorna o nome da fonte. Somente leitura String.

**Retorna:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Retorna o nome da fonte, substituindo a referência do tema por uma fonte real usada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema do qual o nome da fonte temático deve ser obtido. Cabe ao chamador fornecer um valor correto. |

**Retorna:**
java.lang.String - Nome da fonte.