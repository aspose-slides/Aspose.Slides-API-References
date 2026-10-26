---
title: FontData
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una definición de fuente.
type: docs
url: /es/com.aspose.slides/fontdata/
---
**Herencia:**
java.lang.Object

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Representa una definición de fuente. Inmutable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Crea un nuevo objeto FontData con el nombre de fuente especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontName()](#getFontName--) | Devuelve el nombre de la fuente. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Devuelve el nombre de la fuente, sustituyendo la referencia del tema por una fuente real utilizada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si dos instancias de FontData son iguales. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular, adecuada para su uso en algoritmos de hashing y estructuras de datos como una tabla hash. |
| [toString()](#toString--) | Devuelve la representación en cadena. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Crea un nuevo objeto FontData con el nombre de fuente especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
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

Devuelve el nombre de la fuente, sustituyendo la referencia del tema por una fuente real utilizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema del que se debe tomar el nombre de fuente temático. Corresponde al llamador proporcionar un valor correcto. Ver [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Devuelve:**
java.lang.String - Nombre de la fuente.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si dos instancias de FontData son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El FontData a comparar con el FontData actual. |

**Devuelve:**
boolean - **true** si el FontData especificado es igual al FontData actual; de lo contrario, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular, adecuada para su uso en algoritmos de hashing y estructuras de datos como una tabla hash.

**Devuelve:**
int - Código hash del FontData.
### toString() {#toString--}
```
public String toString()
```

Devuelve la representación en cadena.

**Devuelve:**
java.lang.String - Representación en cadena.