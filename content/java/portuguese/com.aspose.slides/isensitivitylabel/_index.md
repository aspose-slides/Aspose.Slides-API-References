---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Representa a etiqueta de sensibilidade do Microsoft Purview Information Protection.
type: docs
url: /pt/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Representa a etiqueta de sensibilidade do Microsoft Purview Information Protection.
## Métodos

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Retorna ou define o id da etiqueta de sensibilidade. |
| [setId(String value)](#setId-java.lang.String-) | Retorna ou define o id da etiqueta de sensibilidade. |
| [getSiteId()](#getSiteId--) | Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política da etiqueta de sensibilidade que descreve a etiqueta de sensibilidade. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política da etiqueta de sensibilidade que descreve a etiqueta de sensibilidade. |
| [isEnabled()](#isEnabled--) | Indica se a etiqueta de sensibilidade está habilitada. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indica se a etiqueta de sensibilidade está habilitada. |
| [isRemoved()](#isRemoved--) | Indica se a etiqueta de sensibilidade foi removida. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indica se a etiqueta de sensibilidade foi removida. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Retorna ou define o método de atribuição para a etiqueta de sensibilidade. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Retorna ou define o método de atribuição para a etiqueta de sensibilidade. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Retorna a lista de tipos de marcação de conteúdo que devem ser aplicados a um arquivo. |
### getId() {#getId--}
```
public abstract String getId()
```


Retorna ou define o id da etiqueta de sensibilidade. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Retorna ou define o id da etiqueta de sensibilidade. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política da etiqueta de sensibilidade que descreve a etiqueta de sensibilidade. Leitura/Gravação java.util.UUID.

**Retorna:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política da etiqueta de sensibilidade que descreve a etiqueta de sensibilidade. Leitura/Gravação java.util.UUID.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Indica se a etiqueta de sensibilidade está habilitada.

**Retorna:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Indica se a etiqueta de sensibilidade está habilitada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Indica se a etiqueta de sensibilidade foi removida.

**Retorna:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Indica se a etiqueta de sensibilidade foi removida.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Retorna ou define o método de atribuição para a etiqueta de sensibilidade. Leitura/Gravação [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Retorna:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Retorna ou define o método de atribuição para a etiqueta de sensibilidade. Leitura/Gravação [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Retorna a lista de tipos de marcação de conteúdo que devem ser aplicados a um arquivo.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Uma lista de tipos de conteúdo [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)