---
title: IFontData
second_title: Aspose.Slides para Android a través de la Referencia de API de Java
description: Representa una definición de fuente.
type: docs
url: /es/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Representa una definición de fuente.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontName()](#getFontName--) | Devuelve el nombre de la fuente. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Devuelve el nombre de la fuente, sustituyendo la referencia de tema por una fuente real utilizada. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Devuelve el nombre de la fuente. Solo lectura String.

**Devuelve:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Devuelve el nombre de la fuente, sustituyendo la referencia de tema por una fuente real utilizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema del cual se debe tomar el nombre de fuente temático. Depende del llamador proporcionar un valor correcto. |

**Devuelve:**
java.lang.String - Nombre de la fuente.