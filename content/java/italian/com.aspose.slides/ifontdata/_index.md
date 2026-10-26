---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
type: docs
url: /it/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Rappresenta una definizione di carattere.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontName()](#getFontName--) | Restituisce il nome del carattere. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Restituisce il nome del carattere, sostituendo il riferimento al tema con un carattere effettivamente utilizzato. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Restituisce il nome del carattere. String di sola lettura.

**Restituisce:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Restituisce il nome del carattere, sostituendo il riferimento al tema con un carattere effettivamente utilizzato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema da cui prendere il nome del carattere tematico. Spetta al chiamante fornire un valore corretto. |

**Restituisce:**
java.lang.String - Nome del carattere.