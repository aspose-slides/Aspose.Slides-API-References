---
title: ISensitivityLabelCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de etiquetas de sensibilidad aplicadas al documento.
type: docs
url: /es/com.aspose.slides/isensitivitylabelcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
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
| [getCount()](#getCount--) | Obtiene el número de todos los elementos en la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Devuelve la etiqueta de sensibilidad por índice. Solo lectura [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
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
public abstract int add(ISensitivityLabel label)
```

Agrega un SensitivityLabel a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | El objeto SensitivityLabel que se agregará al final de la colección. |

**Devuelve:**
int - El índice en el que se agregó el SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina la etiqueta de sensibilidad en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la etiqueta de sensibilidad que debe eliminarse. |
### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los elementos de la colección.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtiene el número de todos los elementos en la colección. Solo lectura  int .

**Devuelve:**
int