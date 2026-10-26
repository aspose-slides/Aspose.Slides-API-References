---
title: SizeF
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Clase para describir dimensiones de ancho y alto en alguna unidad arbitraria con valores de punto flotante.
type: docs
url: /es/com.aspose.slides.android/sizef/
---
**Herencia:**
java.lang.Object
```
public class SizeF
```

Clase para describir dimensiones de ancho y alto en alguna unidad arbitraria con valores de punto flotante.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Create a new SizeF instance. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Get the width of the size. |
| [getHeight()](#getHeight--) | Get the height of the size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if this size is equal to another size. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Return the size represented as a string with the format  "WxH"  |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

Crea una nueva instancia de SizeF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | float | El ancho del tamaño |
| height | float | La altura del tamaño |

### getWidth() {#getWidth--}
```
public float getWidth()
```

Obtiene el ancho del tamaño.

**Devuelve:**
float - width

### getHeight() {#getHeight--}
```
public float getHeight()
```

Obtiene la altura del tamaño.

**Devuelve:**
float - height

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Comprueba si este tamaño es igual a otro tamaño.

Dos tamaños son iguales si y solo si sus anchos y alturas son idénticos.

Para este propósito, los valores float de ancho/altura se consideran iguales si y solo si el método Float#floatToIntBits(float).floatToIntBits(float) devuelve el mismo valor int cuando se aplica a cada uno.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Devuelve:**
boolean - true si los objetos eran iguales, false en caso contrario

### hashCode() {#hashCode--}
```
public int hashCode()
```

**Devuelve:**
int

### toString() {#toString--}
```
public String toString()
```

Devuelve el tamaño representado como una cadena con el formato "WxH"

**Devuelve:**
java.lang.String - representación en cadena del tamaño