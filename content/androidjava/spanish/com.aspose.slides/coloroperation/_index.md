---
title: ColorOperation
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa diferentes operaciones de color utilizadas para transformaciones de color.
type: docs
url: /es/com.aspose.slides/coloroperation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Representa diferentes operaciones de color utilizadas para transformaciones de color. Objeto inmutable.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Crea una nueva operación de transformación de color. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Crea una nueva operación de transformación de color. |
## Methods

| Método | Descripción |
| --- | --- |
| [getOperationType()](#getOperationType--) | Devuelve o establece el tipo de una operación. |
| [getParameter()](#getParameter--) | Devuelve un parámetro de una operación. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si las dos instancias de ColorOperation son iguales. |
| [hashCode()](#hashCode--) | Sirve como una función hash para un tipo particular, adecuada para su uso en algoritmos de hash y estructuras de datos como una tabla hash. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Crea una nueva operación de transformación de color.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| op | int | Tipo de operación. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Crea una nueva operación de transformación de color.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| op | int | Tipo de operación. |
| parameter | float | Parámetro de la operación. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


Devuelve o establece el tipo de una operación. Solo lectura [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Devuelve:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


Devuelve un parámetro de una operación. Solo lectura float.

**Devuelve:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si las dos instancias de ColorOperation son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | |
| obj | java.lang.Object | El ColorOperation a comparar con el ColorOperation actual. |

**Devuelve:**
boolean - **true** if the specified ColorOperation is equal to the current ColorOperation; otherwise, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como una función hash para un tipo particular, adecuada para su uso en algoritmos de hash y estructuras de datos como una tabla hash.

**Devuelve:**
int