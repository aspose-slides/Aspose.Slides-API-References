---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Representa uma definição de fonte.
type: docs
url: /pt/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Representa uma definição de fonte.
## Métodos

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Retorna o nome da fonte. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Retorna o nome da fonte, substituindo a referência ao tema por uma fonte real usada. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Retorna o nome da fonte. String somente leitura.

**Retorna:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Retorna o nome da fonte, substituindo a referência ao tema por uma fonte real usada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema do qual o nome da fonte temático deve ser obtido. É responsabilidade do chamador fornecer um valor correto. |

**Retorna:**
java.lang.String - Nome da fonte.