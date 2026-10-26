---
title: IBehaviorPropertyCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa las propiedades de temporización para el comportamiento del efecto.
type: docs
url: /es/com.aspose.slides/ibehaviorpropertycollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Representa propiedades de temporización para el comportamiento del efecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Agrega una nueva propiedad a la colección. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina el índice de un elemento específico por el valor de la propiedad en la List. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserta una nueva propiedad (con el valor de propiedad especificado) en la colección en el índice especificado. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Elimina la propiedad especificada de la colección. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


Agrega una nueva propiedad a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor de la propiedad a agregar. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


Determina el índice de un elemento específico por el valor de la propiedad en la List.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | valor de la propiedad |

**Devuelve:**
int - The index of the property with the specified value
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


Inserta una nueva propiedad (con el valor de propiedad especificado) en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice donde se debe insertar una nueva propiedad. |
| propertyValue | java.lang.String | Valor de la propiedad a agregar. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


Elimina la propiedad especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor de la propiedad a eliminar. |

**Devuelve:**
boolean - True si una propiedad se eliminó correctamente boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor de la propiedad a localizar en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si propertyValue se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false.