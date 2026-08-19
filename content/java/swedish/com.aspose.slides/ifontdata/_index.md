---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
type: docs
url: /sv/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Representerar en teckensnittsdefinition.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontName()](#getFontName--) | Returnerar teckensnittsnamnet. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returnerar teckensnittsnamnet och ersätter temareferensen med ett faktiskt använt teckensnitt. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Returnerar teckensnittsnamnet. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Returnerar teckensnittsnamnet och ersätter temareferensen med ett faktiskt använt teckensnitt.

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema som det tematiska teckensnittsnamnet ska tas från. Det är upp till anroparen att tillhandahålla ett korrekt värde. |

**Returnerar:**
java.lang.String - Teckensnittsnamn.