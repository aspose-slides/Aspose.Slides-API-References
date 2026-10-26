---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a font definition.
type: docs
url: /it/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Rappresenta una definizione di font.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontName()](#getFontName--) | Restituisce il nome del font. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Restituisce il nome del font, sostituendo il riferimento al tema con un font effettivamente utilizzato. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Restituisce il nome del font. String di sola lettura.

**Restituisce:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Restituisce il nome del font, sostituendo il riferimento al tema con un font effettivamente utilizzato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema da cui dovrebbe essere preso il nome del font tematico. Spetta al chiamante fornire un valore corretto. |

**Restituisce:**
java.lang.String - Nome del font.