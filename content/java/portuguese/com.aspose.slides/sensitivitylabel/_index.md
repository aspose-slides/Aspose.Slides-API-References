---
title: SensitivityLabel
second_title: Referência da API Aspose.Slides para Java
description: Representa o rótulo de sensibilidade do Microsoft Purview Information Protection.
type: docs
url: /pt/com.aspose.slides/sensitivitylabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Representa o rótulo de sensibilidade do Microsoft Purview Information Protection.
## Métodos

| Método | Descrição |
| --- | --- |
| [getId()](#getId--) | Retorna ou define o id do rótulo de sensibilidade. |
| [setId(String value)](#setId-java.lang.String-) | Retorna ou define o id do rótulo de sensibilidade. |
| [getSiteId()](#getSiteId--) | Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política do rótulo de sensibilidade que descreve o rótulo de sensibilidade. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política do rótulo de sensibilidade que descreve o rótulo de sensibilidade. |
| [isEnabled()](#isEnabled--) | Indica se o rótulo de sensibilidade está habilitado. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indica se o rótulo de sensibilidade está habilitado. |
| [isRemoved()](#isRemoved--) | Indica se o rótulo de sensibilidade foi removido. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indica se o rótulo de sensibilidade foi removido. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Retorna ou define o método de atribuição para o rótulo de sensibilidade. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Retorna ou define o método de atribuição para o rótulo de sensibilidade. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Retorna a lista de tipos de marcação de conteúdo que devem ser aplicados a um arquivo. |
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

Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política do rótulo de sensibilidade que descreve o rótulo de sensibilidade. Leitura/gravação java.util.UUID.

**Retorna:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Retorna ou define o identificador do site do Azure Active Directory (Azure AD) correspondente à política do rótulo de sensibilidade que descreve o rótulo de sensibilidade. Leitura/gravação java.util.UUID.

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