---
title: SensitivityLabel
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta l'etichetta di sensibilità di Microsoft Purview Information Protection.
type: docs
url: /it/com.aspose.slides/sensitivitylabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Rappresenta l'etichetta di sensibilità di Microsoft Purview Information Protection.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getId()](#getId--) | Restituisce o imposta l'id dell'etichetta di sensibilità. |
| [setId(String value)](#setId-java.lang.String-) | Restituisce o imposta l'id dell'etichetta di sensibilità. |
| [getSiteId()](#getSiteId--) | Restituisce o imposta l'identificatore del sito Azure Active Directory (Azure AD) corrispondente alla politica dell'etichetta di sensibilità che descrive l'etichetta di sensibilità. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Restituisce o imposta l'identificatore del sito Azure Active Directory (Azure AD) corrispondente alla politica dell'etichetta di sensibilità che descrive l'etichetta di sensibilità. |
| [isEnabled()](#isEnabled--) | Indica se l'etichetta di sensibilità è abilitata. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indica se l'etichetta di sensibilità è abilitata. |
| [isRemoved()](#isRemoved--) | Indica se l'etichetta di sensibilità è stata rimossa. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indica se l'etichetta di sensibilità è stata rimossa. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Restituisce o imposta il metodo di assegnazione per l'etichetta di sensibilità. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Restituisce o imposta il metodo di assegnazione per l'etichetta di sensibilità. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Restituisce l'elenco dei tipi di marcatura del contenuto che dovrebbero essere applicati a un file. |

### getId() {#getId--}
```
public final String getId()
```

Restituisce o imposta l'id dell'etichetta di sensibilità. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Restituisce o imposta l'id dell'etichetta di sensibilità. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Restituisce o imposta l'identificatore del sito Azure Active Directory (Azure AD) corrispondente alla politica dell'etichetta di sensibilità che descrive l'etichetta di sensibilità. Lettura/scrittura java.util.UUID.

**Restituisce:**
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Restituisce o imposta l'identificatore del sito Azure Active Directory (Azure AD) corrispondente alla politica dell'etichetta di sensibilità che descrive l'etichetta di sensibilità. Lettura/scrittura java.util.UUID.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Indica se l'etichetta di sensibilità è abilitata.

**Restituisce:**
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Indica se l'etichetta di sensibilità è abilitata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Indica se l'etichetta di sensibilità è stata rimossa.

**Restituisce:**
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Indica se l'etichetta di sensibilità è stata rimossa.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Restituisce o imposta il metodo di assegnazione per l'etichetta di sensibilità. Lettura/scrittura [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Restituisce:**
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Restituisce o imposta il metodo di assegnazione per l'etichetta di sensibilità. Lettura/scrittura [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Restituisce l'elenco dei tipi di marcatura del contenuto che dovrebbero essere applicati a un file.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)