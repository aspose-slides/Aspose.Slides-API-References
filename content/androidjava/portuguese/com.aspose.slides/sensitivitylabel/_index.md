---
title: SensitivityLabel
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa o rótulo de sensibilidade do Microsoft Purview Information Protection.
type: docs
url: /pt/com.aspose.slides/sensitivitylabel/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Representa o rótulo de sensibilidade do Microsoft Purview Information Protection.
## Métodos

| MéTODO | Descrição |
| --- | --- |
| [getId()](#getId--) | Returns or sets the id of sensitivity label. |
| [setId(String value)](#setId-java.lang.String-) | Returns or sets the id of sensitivity label. |
| [getSiteId()](#getSiteId--) | Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. |
| [isEnabled()](#isEnabled--) | Indicates whether the sensitivity label is enabled. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indicates whether the sensitivity label is enabled. |
| [isRemoved()](#isRemoved--) | Indicates whether the sensitivity label was removed. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indicates whether the sensitivity label was removed. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Returns or sets the assignment method for the sensitivity label. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Returns or sets the assignment method for the sensitivity label. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Returns the list of types of content marking that ought to be applied to a file. |
### getId() {#getId--}
```
public final String getId()
```


Retorna ou define o id do rótulo de sensibilidade. Leitura/gravação String.

**Retorna:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Retorna ou define o id do rótulo de sensibilidade. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política de rótulo de sensibilidade que descreve o rótulo de sensibilidade. Leitura/gravação java.util.UUID.

**Retorna:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política de rótulo de sensibilidade que descreve o rótulo de sensibilidade. Leitura/gravação java.util.UUID.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Indica se o rótulo de sensibilidade está habilitado.

**Retorna:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Indica se o rótulo de sensibilidade está habilitado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Indica se o rótulo de sensibilidade foi removido.

**Retorna:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Indica se o rótulo de sensibilidade foi removido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Retorna ou define o método de atribuição para o rótulo de sensibilidade. Leitura/gravação [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Retorna:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Retorna ou define o método de atribuição para o rótulo de sensibilidade. Leitura/gravação [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Retorna a lista de tipos de marcação de conteúdo que devem ser aplicados a um arquivo.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Uma lista de tipos de conteúdo [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)