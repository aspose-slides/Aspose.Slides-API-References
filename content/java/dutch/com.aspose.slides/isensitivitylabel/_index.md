---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /nl/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Geeft het gevoeligheidslabel weer uit Microsoft Purview Information Protection.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getId()](#getId--) | Geeft of stelt de id van het gevoeligheidslabel in. |
| [setId(String value)](#setId-java.lang.String-) | Geeft of stelt de id van het gevoeligheidslabel in. |
| [getSiteId()](#getSiteId--) | Geeft of stelt de Azure Active Directory (Azure AD) site-identificatie die overeenkomt met het gevoeligheidslabel-beleid dat het gevoeligheidslabel beschrijft, in. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Geeft of stelt de Azure Active Directory (Azure AD) site-identificatie die overeenkomt met het gevoeligheidslabel-beleid dat het gevoeligheidslabel beschrijft, in. |
| [isEnabled()](#isEnabled--) | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| [isRemoved()](#isRemoved--) | Geeft aan of het gevoeligheidslabel is verwijderd. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Geeft aan of het gevoeligheidslabel is verwijderd. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Geeft de lijst met typen inhoudsmarkering die op een bestand moeten worden toegepast. |
### getId() {#getId--}
```
public abstract String getId()
```

Geeft of stelt de id van het gevoeligheidslabel in. Lezen/schrijven String.

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Geeft of stelt de id van het gevoeligheidslabel in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Geeft of stelt de Azure Active Directory (Azure AD) site-identificatie die overeenkomt met het gevoeligheidslabel-beleid dat het gevoeligheidslabel beschrijft, in. Lezen/schrijven java.util.UUID.

**Returns:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Geeft of stelt de Azure Active Directory (Azure AD) site-identificatie die overeenkomt met het gevoeligheidslabel-beleid dat het gevoeligheidslabel beschrijft, in. Lezen/schrijven java.util.UUID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Geeft aan of het gevoeligheidslabel is ingeschakeld.

**Returns:**
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

**Returns:**
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

Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. Lezen/schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returns:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. Lezen/schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Geeft de lijst met typen inhoudsmarkering die op een bestand moeten worden toegepast.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Een lijst met inhoudstypen [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)