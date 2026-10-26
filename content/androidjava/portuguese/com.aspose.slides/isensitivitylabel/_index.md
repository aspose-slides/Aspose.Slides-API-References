---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /pt/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Representa o rótulo de sensibilidade do Microsoft Purview Information Protection.
## Métodos

| Método | Descrição |
| --- | --- |
| [getId()](#getId--) | Retorna ou define o id do rótulo de sensibilidade. |
| [setId(String value)](#setId-java.lang.String-) | Retorna ou define o id do rótulo de sensibilidade. |
| [getSiteId()](#getSiteId--) | Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política de rótulo de sensibilidade que descreve o rótulo de sensibilidade. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política de rótulo de sensibilidade que descreve o rótulo de sensibilidade. |
| [isEnabled()](#isEnabled--) | Indica se o rótulo de sensibilidade está habilitado. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indica se o rótulo de sensibilidade está habilitado. |
| [isRemoved()](#isRemoved--) | Indica se o rótulo de sensibilidade foi removido. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indica se o rótulo de sensibilidade foi removido. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Retorna ou define o método de atribuição para o rótulo de sensibilidade. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Retorna ou define o método de atribuição para o rótulo de sensibilidade. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Retorna a lista de tipos de marcação de conteúdo que devem ser aplicados a um arquivo. |
### getId() {#getId--}
```
public abstract String getId()
```


Retorna ou define o id do rótulo de sensibilidade. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Retorna ou define o id do rótulo de sensibilidade. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política de rótulo de sensibilidade que descreve o rótulo de sensibilidade. Leitura/Gravação java.util.UUID.

**Retorna:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política de rótulo de sensibilidade que descreve o rótulo de sensibilidade. Leitura/Gravação java.util.UUID.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Indica se o rótulo de sensibilidade está habilitado.

**Retorna:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Indica se o rótulo de sensibilidade está habilitado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Indica se o rótulo de sensibilidade foi removido.

**Retorna:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Indica se o rótulo de sensibilidade foi removido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Retorna ou define o método de atribuição para o rótulo de sensibilidade. Leitura/Gravação [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Retorna:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Retorna ou define o método de atribuição para o rótulo de sensibilidade. Leitura/Gravação [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

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