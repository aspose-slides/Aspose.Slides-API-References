---
title: FontData
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una definición de fuente.
type: docs
url: /es/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Representa una definición de fuente. Inmutable.
## Constructores

| Constructor | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Crea un nuevo objeto FontData con el nombre de fuente especificado. |
## Métodos

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Devuelve el nombre de la fuente. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Devuelve el nombre de la fuente, sustituyendo la referencia de tema por una fuente real utilizada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si dos instancias de FontData son iguales. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular, adecuada para usar en algoritmos de hashing y estructuras de datos como una tabla hash. |
| [toString()](#toString--) | Devuelve la representación en cadena. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Crea un nuevo objeto FontData con el nombre de fuente especificado.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Devuelve el nombre de la fuente. Lectura/escritura String.

**Devuelve:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Devuelve el nombre de la fuente, sustituyendo la referencia de tema por una fuente real utilizada.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema del que se debe tomar el nombre de fuente temático. Corresponde al llamador proporcionar un valor correcto. Vea [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Devuelve:**
java.lang.String - Nombre de la fuente.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si dos instancias de FontData son iguales.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | La FontData con la que comparar la FontData actual. |

**Devuelve:**
boolean - **true** si la FontData especificada es igual a la FontData actual; de lo contrario, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular, adecuada para usar en algoritmos de hashing y estructuras de datos como una tabla hash.

**Devuelve:**
int - Código hash de la FontData.
### toString() {#toString--}
```
public String toString()
```

Devuelve la representación en cadena.

**Devuelve:**
java.lang.String - Representación en cadena.