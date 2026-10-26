---
title: Size
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Clase para describir dimensiones de ancho y alto en alguna unidad arbitraria.
type: docs
url: /es/com.aspose.slides.android/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Clase para describir dimensiones de ancho y alto en alguna unidad arbitraria.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Create a new Size instance. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Obtiene el ancho del size. |
| [getHeight()](#getHeight--) | Obtiene el alto del size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si este size es igual a otro size. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Devuelve el size representado como una cadena con el formato "WxH" |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Crea una nueva instancia de Size.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho del size |
| height | int | El alto del size |

### getWidth() {#getWidth--}
```
public int getWidth()
```

Obtiene el ancho del size.

**Devuelve:**
int - ancho

### getHeight() {#getHeight--}
```
public int getHeight()
```

Obtiene el alto del size.

**Devuelve:**
int - alto

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Comprueba si este size es igual a otro size.

Dos size son iguales si y solo si tanto sus anchos como sus altos son iguales.

Un objeto size nunca es igual a ningún otro tipo de objeto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Devuelve:**
boolean -  true  si los objetos eran iguales,  false  de lo contrario

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

Devuelve el size representado como una cadena con el formato "WxH"

**Devuelve:**
java.lang.String - representación en cadena del size