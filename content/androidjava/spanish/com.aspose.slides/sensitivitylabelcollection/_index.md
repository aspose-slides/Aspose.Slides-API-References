---
title: SensitivityLabelCollection
second_title: Aspose.Slides para Android mediante la Referencia de la API Java
description: Representa una colección de etiquetas de sensibilidad aplicadas al documento.
type: docs
url: /es/com.aspose.slides/sensitivitylabelcollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Representa una colección de etiquetas de sensibilidad aplicadas al documento.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la etiqueta de sensibilidad por índice. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Agrega la etiqueta de sensibilidad al final de la colección. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Agrega un SensitivityLabel a la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la etiqueta de sensibilidad en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [getCount()](#getCount--) | Devuelve el número de elementos en la colección. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Copia todos los elementos de la colección al arreglo especificado. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

Devuelve la etiqueta de sensibilidad por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Agrega la etiqueta de sensibilidad al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | java.lang.String | El id de la etiqueta de sensibilidad. |
| siteId | java.util.UUID | El identificador del sitio de Azure Active Directory (Azure AD). |
| isEnabled | boolean | Bandera que indica si la etiqueta de sensibilidad está habilitada. |
| methodType | int | El método de asignación para la etiqueta de sensibilidad. |

**Devuelve:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

Agrega un SensitivityLabel a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | El objeto SensitivityLabel que será agregado al final de la colección. |

**Devuelve:**
int - El índice en el que se añadió el SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina la etiqueta de sensibilidad en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la etiqueta de sensibilidad que debe ser eliminada. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los elementos de la colección.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Un  System.Collections.Generic.IEnumerator1  que puede usarse para iterar a través de la colección.
### getCount() {#getCount--}
```
public final int getCount()
```

Devuelve el número de elementos en la colección. Solo lectura  int .

**Devuelve:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

Copia todos los elementos de la colección al arreglo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Arreglo de destino. |
| index | int | Índice inicial en el arreglo de destino. |