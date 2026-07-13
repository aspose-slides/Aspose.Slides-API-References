---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar en fontdefinition.
type: docs
url: /sv/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Representerar en fontdefinition.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontName()](#getFontName--) | Returnerar fontnamnet. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returnerar fontnamnet och ersätter temareferens med den faktiska använda fonten. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Returnerar fontens namn. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Returnerar fontens namn och ersätter temareferens med den faktiska använda fonten.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema som det tematiska fontnamnet ska tas från. Det är upp till anroparen att tillhandahålla ett korrekt värde. |

**Returnerar:**
java.lang.String - Fontnamn.