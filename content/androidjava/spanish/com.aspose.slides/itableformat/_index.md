---
title: ITableFormat
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa el formato de una tabla.
type: docs
url: /es/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Representa el formato de una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Devuelve un objeto de propiedades de relleno de tabla. |
| [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia del color de relleno. |
| [setTransparency(float value)](#setTransparency-float-) | Obtiene o establece la transparencia del color de relleno. |
| [getEffective()](#getEffective--) | Obtiene las propiedades de formato de tabla efectivas con herencia y estilos de tabla aplicados. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Devuelve un objeto de propiedades de relleno de tabla. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Obtiene o establece la transparencia del color de relleno. Lectura/escritura  float .

**Devuelve:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Obtiene o establece la transparencia del color de relleno. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

Obtiene las propiedades de formato de tabla efectivas con herencia y estilos de tabla aplicados.

**Devuelve:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Un [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).