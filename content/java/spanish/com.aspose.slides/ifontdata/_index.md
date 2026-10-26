---
title: IFontData
second_title: Aspose.Slides para la API de Java
description: Representa una definición de fuente.
type: docs
url: /es/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Representa una definición de fuente.
## Métodos

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Devuelve el nombre de la fuente. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Devuelve el nombre de la fuente, sustituyendo la referencia del tema por una fuente real utilizada. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Devuelve el nombre de la fuente. Solo lectura String.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Devuelve el nombre de la fuente, sustituyendo la referencia del tema por una fuente real utilizada.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema del que se debe obtener el nombre de la fuente con tema. Corresponde al llamador proporcionar un valor correcto. |

**Returns:**
java.lang.String - nombre de la fuente.