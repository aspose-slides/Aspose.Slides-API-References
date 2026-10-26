---
title: SensitivityLabel
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje štítek citlivosti ze služby Microsoft Purview Information Protection.
type: docs
url: /cs/com.aspose.slides/sensitivitylabel/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Představuje štítek citlivosti z Microsoft Purview Information Protection.
## Metody

| Metoda | Popis |
| --- | --- |
| [getId()](#getId--) | Vrací nebo nastavuje id štítku citlivosti. |
| [setId(String value)](#setId-java.lang.String-) | Vrací nebo nastavuje id štítku citlivosti. |
| [getSiteId()](#getSiteId--) | Vrací nebo nastavuje identifikátor místa Azure Active Directory (Azure AD) odpovídající politice štítku citlivosti, která štítek popisuje. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Vrací nebo nastavuje identifikátor místa Azure Active Directory (Azure AD) odpovídající politice štítku citlivosti, která štítek popisuje. |
| [isEnabled()](#isEnabled--) | Udává, zda je štítek citlivosti povolen. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Udává, zda je štítek citlivosti povolen. |
| [isRemoved()](#isRemoved--) | Udává, zda byl štítek citlivosti odstraněn. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Udává, zda byl štítek citlivosti odstraněn. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Vrací nebo nastavuje metodu přiřazení pro štítek citlivosti. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Vrací nebo nastavuje metodu přiřazení pro štítek citlivosti. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Vrací seznam typů označování obsahu, které mají být použity na soubor. |
### getId() {#getId--}
```
public final String getId()
```


Vrací nebo nastavuje id štítku citlivosti. Číst/zapisovat String.

**Vrací:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Vrací nebo nastavuje id štítku citlivosti. Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Vrací nebo nastavuje identifikátor místa Azure Active Directory (Azure AD) odpovídající politice štítku citlivosti, která štítek popisuje. Číst/zapisovat java.util.UUID.

**Vrací:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Vrací nebo nastavuje identifikátor místa Azure Active Directory (Azure AD) odpovídající politice štítku citlivosti, která štítek popisuje. Číst/zapisovat java.util.UUID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Udává, zda je štítek citlivosti povolen.

**Vrací:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Udává, zda je štítek citlivosti povolen.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Udává, zda byl štítek citlivosti odstraněn.

**Vrací:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Udává, zda byl štítek citlivosti odstraněn.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Vrací nebo nastavuje metodu přiřazení pro štítek citlivosti. Číst/zapisovat [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Vrací:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Vrací nebo nastavuje metodu přiřazení pro štítek citlivosti. Číst/zapisovat [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Vrací seznam typů označování obsahu, které mají být použity na soubor.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Seznam typů obsahu [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)