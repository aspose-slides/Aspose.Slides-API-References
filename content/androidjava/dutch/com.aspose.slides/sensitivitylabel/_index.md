---
title: SensitivityLabel
second_title: Aspose.Slides voor Android via Java API Referentie
description: Vertegenwoordigt het gevoeligheidslabel van Microsoft Purview Information Protection.
type: docs
url: /nl/com.aspose.slides/sensitivitylabel/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Vertegenwoordigt het gevoeligheidslabel van Microsoft Purview Information Protection.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getId()](#getId--) | Retourneert of stelt de id van het gevoeligheidslabel in. |
| [setId(String value)](#setId-java.lang.String-) | Retourneert of stelt de id van het gevoeligheidslabel in. |
| [getSiteId()](#getSiteId--) | Retourneert of stelt de Azure Active Directory (Azure AD) site-identificatie in die overeenkomt met het beleid voor het gevoeligheidslabel dat het gevoeligheidslabel beschrijft. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Retourneert of stelt de Azure Active Directory (Azure AD) site-identificatie in die overeenkomt met het beleid voor het gevoeligheidslabel dat het gevoeligheidslabel beschrijft. |
| [isEnabled()](#isEnabled--) | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| [isRemoved()](#isRemoved--) | Geeft aan of het gevoeligheidslabel is verwijderd. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Geeft aan of het gevoeligheidslabel is verwijderd. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Retourneert of stelt de toewijzingsmethode voor het gevoeligheidslabel in. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Retourneert of stelt de toewijzingsmethode voor het gevoeligheidslabel in. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Retourneert de lijst met typen inhoudmarkering die op een bestand moet worden toegepast. |
### getId() {#getId--}
```
public final String getId()
```

Retourneert of stelt de id van het gevoeligheidslabel in. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Retourneert of stelt de id van het gevoeligheidslabel in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Retourneert of stelt de Azure Active Directory (Azure AD) site-identificatie in die overeenkomt met het beleid voor het gevoeligheidslabel dat het gevoeligheidslabel beschrijft. Lezen/schrijven java.util.UUID.

**Retourneert:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Retourneert of stelt de Azure Active Directory (Azure AD) site-identificatie in die overeenkomt met het beleid voor het gevoeligheidslabel dat het gevoeligheidslabel beschrijft. Lezen/schrijven java.util.UUID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Geeft aan of het gevoeligheidslabel is ingeschakeld.

**Retourneert:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Geeft aan of het gevoeligheidslabel is ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Geeft aan of het gevoeligheidslabel is verwijderd.

**Retourneert:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Geeft aan of het gevoeligheidslabel is verwijderd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Retourneert of stelt de toewijzingsmethode voor het gevoeligheidslabel in. Lezen/schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Retourneert:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Retourneert of stelt de toewijzingsmethode voor het gevoeligheidslabel in. Lezen/schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Retourneert de lijst met typen inhoudmarkering die op een bestand moet worden toegepast.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Een lijst met inhoudstypen [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)