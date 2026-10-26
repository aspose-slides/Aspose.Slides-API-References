---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /cs/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Represents the sensitivity label from Microsoft Purview Information Protection.
## Metody

| Metoda | Popis |
| --- | --- |
| [getId()](#getId--) | Vrací nebo nastavuje id štítku citlivosti. |
| [setId(String value)](#setId-java.lang.String-) | Vrací nebo nastavuje id štítku citlivosti. |
| [getSiteId()](#getSiteId--) | Vrací nebo nastavuje identifikátor Azure Active Directory (Azure AD) webu odpovídající politice štítku citlivosti, která štítek popisuje. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Vrací nebo nastavuje identifikátor Azure Active Directory (Azure AD) webu odpovídající politice štítku citlivosti, která štítek popisuje. |
| [isEnabled()](#isEnabled--) | Udává, zda je štítek citlivosti povolen. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Udává, zda je štítek citlivosti povolen. |
| [isRemoved()](#isRemoved--) | Udává, zda byl štítek citlivosti odstraněn. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Udává, zda byl štítek citlivosti odstraněn. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Vrací nebo nastavuje způsob přiřazení štítku citlivosti. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Vrací nebo nastavuje způsob přiřazení štítku citlivosti. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Vrací seznam typů označení obsahu, které mají být použity na soubor. |
### getId() {#getId--}
```
public abstract String getId()
```


Vrací nebo nastavuje id štítku citlivosti. Čtení / zápis String.

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Vrací nebo nastavuje id štítku citlivosti. Čtení / zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Vrací nebo nastavuje identifikátor Azure Active Directory (Azure AD) webu odpovídající politice štítku citlivosti, která štítek popisuje. Čtení / zápis java.util.UUID.

**Returns:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Vrací nebo nastavuje identifikátor Azure Active Directory (Azure AD) webu odpovídající politice štítku citlivosti, která štítek popisuje. Čtení / zápis java.util.UUID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Udává, zda je štítek citlivosti povolen.

**Returns:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Udává, zda je štítek citlivosti povolen.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Udává, zda byl štítek citlivosti odstraněn.

**Returns:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Udává, zda byl štítek citlivosti odstraněn.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Vrací nebo nastavuje způsob přiřazení štítku citlivosti. Čtení / zápis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returns:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Vrací nebo nastavuje způsob přiřazení štítku citlivosti. Čtení / zápis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Vrací seznam typů označení obsahu, které mají být použity na soubor.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Seznam typů obsahu [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)