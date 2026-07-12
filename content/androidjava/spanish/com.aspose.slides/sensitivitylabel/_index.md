---
title: SensitivityLabel
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa la etiqueta de sensibilidad de Microsoft Purview Information Protection.
type: docs
url: /es/com.aspose.slides/sensitivitylabel/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Representa la etiqueta de sensibilidad de Microsoft Purview Information Protection.
## Métodos

| Método | Descripción |
| --- | --- |
| [getId()](#getId--) | Devuelve o establece el id de la etiqueta de sensibilidad. |
| [setId(String value)](#setId-java.lang.String-) | Devuelve o establece el id de la etiqueta de sensibilidad. |
| [getSiteId()](#getSiteId--) | Devuelve o establece el identificador del sitio de Azure Active Directory (Azure AD) correspondiente a la política de etiqueta de sensibilidad que describe la etiqueta de sensibilidad. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Devuelve o establece el identificador del sitio de Azure Active Directory (Azure AD) correspondiente a la política de etiqueta de sensibilidad que describe la etiqueta de sensibilidad. |
| [isEnabled()](#isEnabled--) | Indica si la etiqueta de sensibilidad está habilitada. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indica si la etiqueta de sensibilidad está habilitada. |
| [isRemoved()](#isRemoved--) | Indica si la etiqueta de sensibilidad fue eliminada. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indica si la etiqueta de sensibilidad fue eliminada. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Devuelve o establece el método de asignación para la etiqueta de sensibilidad. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Devuelve o establece el método de asignación para la etiqueta de sensibilidad. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Devuelve la lista de tipos de marcado de contenido que deben aplicarse a un archivo. |
### getId() {#getId--}
```
public final String getId()
```

Devuelve o establece el id de la etiqueta de sensibilidad. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Devuelve o establece el id de la etiqueta de sensibilidad. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Devuelve o establece el identificador del sitio de Azure Active Directory (Azure AD) correspondiente a la política de etiqueta de sensibilidad que describe la etiqueta de sensibilidad. Lectura/escritura java.util.UUID.

**Devuelve:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Devuelve o establece el identificador del sitio de Azure Active Directory (Azure AD) correspondiente a la política de etiqueta de sensibilidad que describe la etiqueta de sensibilidad. Lectura/escritura java.util.UUID.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Indica si la etiqueta de sensibilidad está habilitada.

**Devuelve:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Indica si la etiqueta de sensibilidad está habilitada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Indica si la etiqueta de sensibilidad fue eliminada.

**Devuelve:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Indica si la etiqueta de sensibilidad fue eliminada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Devuelve o establece el método de asignación para la etiqueta de sensibilidad. Lectura/escritura [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Devuelve:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Devuelve o establece el método de asignación para la etiqueta de sensibilidad. Lectura/escritura [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Devuelve la lista de tipos de marcado de contenido que deben aplicarse a un archivo.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)