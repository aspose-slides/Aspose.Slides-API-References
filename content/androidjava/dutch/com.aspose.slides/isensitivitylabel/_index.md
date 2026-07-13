---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Vertegenwoordigt het gevoeligheidslabel van Microsoft Purview Information Protection.
type: docs
url: /nl/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Vertegenwoordigt het gevoeligheidslabel van Microsoft Purview Information Protection.
## Methoden

| Methode | Beschrijving |
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
public abstract String getId()
```


Geeft de id van het gevoeligheidslabel terug of stelt deze in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Geeft de id van het gevoeligheidslabel terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Geeft de Azure Active Directory (Azure AD) site identifier terug of stelt deze in die overeenkomt met het gevoeligheidslabel-beleid dat het gevoeligheidslabel beschrijft. Lezen/Schrijven java.util.UUID.

**Retour:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Geeft de Azure Active Directory (Azure AD) site identifier terug of stelt deze in die overeenkomt met het gevoeligheidslabel-beleid dat het gevoeligheidslabel beschrijft. Lezen/Schrijven java.util.UUID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Geeft aan of het gevoeligheidslabel is ingeschakeld.

**Retour:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Geeft aan of het gevoeligheidslabel is ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Geeft aan of het gevoeligheidslabel is verwijderd.

**Retour:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Geeft aan of het gevoeligheidslabel is verwijderd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Geeft de toewijzingsmethode voor het gevoeligheidslabel terug of stelt deze in. Lezen/Schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Retour:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Geeft de toewijzingsmethode voor het gevoeligheidslabel terug of stelt deze in. Lezen/Schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Geeft de lijst van typen inhoudsmarkering terug die op een bestand moeten worden toegepast.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Een lijst van content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)