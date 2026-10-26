---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa las propiedades de temporización del comportamiento del efecto.
type: docs
url: /es/com.aspose.slides/ibehaviorpropertycollection/
---
**Todas las Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Representa las propiedades de temporización del comportamiento del efecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Agrega una nueva propiedad a la colección. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina el índice de un elemento específico por el valor de la propiedad en la Lista. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserta una nueva propiedad (con el valor de propiedad especificado) en la colección en el índice especificado. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Elimina la propiedad especificada de la colección. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
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

Determina el índice de un elemento específico por el valor de la propiedad en la Lista.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | valor de la propiedad |

**Devuelve:**
int - El índice de la propiedad con el valor especificado

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
boolean - Verdadero si una propiedad se eliminó correctamente boolean

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor de la propiedad a localizar en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - verdadero si propertyValue se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, falso