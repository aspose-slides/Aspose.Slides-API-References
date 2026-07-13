---
title: ISensitivityLabel
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje citlivostní štítek ze služby Microsoft Purview Information Protection.
type: docs
url: /cs/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Představuje citlivostní štítek ze služby Microsoft Purview Information Protection.

## Metody

| Metoda | Popis |
| --- | --- |
| [getId()](#getId--) | Vrací nebo nastavuje id citlivostního štítku. |
| [setId(String value)](#setId-java.lang.String-) | Vrací nebo nastavuje id citlivostního štítku. |
| [getSiteId()](#getSiteId--) | Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá politice citlivostního štítku popisující tento štítek. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá politice citlivostního štítku popisující tento štítek. |
| [isEnabled()](#isEnabled--) | Určuje, zda je citlivostní štítek povolen. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Určuje, zda je citlivostní štítek povolen. |
| [isRemoved()](#isRemoved--) | Určuje, zda byl citlivostní štítek odstraněn. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Určuje, zda byl citlivostní štítek odstraněn. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Vrací nebo nastavuje metodu přiřazení pro citlivostní štítek. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Vrací nebo nastavuje metodu přiřazení pro citlivostní štítek. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Vrací seznam typů označování obsahu, které by měly být použity na soubor. |

### getId() {#getId--}
```
public abstract String getId()
```

Vrací nebo nastavuje id citlivostního štítku. Čtení/zápis String.

**Vrací:**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Vrací nebo nastavuje id citlivostního štítku. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá politice citlivostního štítku popisující tento štítek. Čtení/zápis java.util.UUID.

**Vrací:**
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá politice citlivostního štítku popisující tento štítek. Čtení/zápis java.util.UUID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Určuje, zda je citlivostní štítek povolen.

**Vrací:**
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Určuje, zda je citlivostní štítek povolen.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Určuje, zda byl citlivostní štítek odstraněn.

**Vrací:**
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Určuje, zda byl citlivostní štítek odstraněn.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Vrací nebo nastavuje metodu přiřazení pro citlivostní štítek. Čtení/zápis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Vrací:**
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Vrací nebo nastavuje metodu přiřazení pro citlivostní štítek. Čtení/zápis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Vrací seznam typů označování obsahu, které by měly být použity na soubor.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Seznam typů obsahu [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)