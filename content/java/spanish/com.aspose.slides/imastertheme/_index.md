---
title: IMasterTheme
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un tema maestro.
type: docs
url: /es/com.aspose.slides/imastertheme/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Representa un tema maestro.
## Métodos

| Método | Descripción |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Devuelve la colección de esquemas de color adicionales. |
| [getName()](#getName--) | Devuelve el nombre de un tema. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve el nombre de un tema. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Devuelve la colección de esquemas de color adicionales. Estos esquemas no afectan al aspecto de la presentación, pueden seleccionarse como esquema de color principal para una diapositiva. Solo lectura [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Devuelve:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Devuelve el nombre de un tema. Lectura/Escritura String.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Devuelve el nombre de un tema. Lectura/Escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |