---
title: SensitivityLabel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt het gevoeligheidslabel van Microsoft Purview Information Protection voor.
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

Stelt het gevoeligheidslabel van Microsoft Purview Information Protection voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getId()](#getId--) | Geeft of stelt de id van het gevoeligheidslabel in. |
| [setId(String value)](#setId-java.lang.String-) | Geeft of stelt de id van het gevoeligheidslabel in. |
| [getSiteId()](#getSiteId--) | Geeft of stelt de Azure Active Directory (Azure AD) site-identifier weer die overeenkomt met het gevoeligheidslabelbeleid dat het gevoeligheidslabel beschrijft. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Geeft of stelt de Azure Active Directory (Azure AD) site-identifier weer die overeenkomt met het gevoeligheidslabelbeleid dat het gevoeligheidslabel beschrijft. |
| [isEnabled()](#isEnabled--) | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| [isRemoved()](#isRemoved--) | Geeft aan of het gevoeligheidslabel is verwijderd. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Geeft aan of het gevoeligheidslabel is verwijderd. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Geeft de lijst van typen inhoudsmarkering die op een bestand moeten worden toegepast. |
### getId() {#getId--}
```
public final String getId()
```

Geeft of stelt de id van het gevoeligheidslabel in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Geeft of stelt de id van het gevoeligheidslabel in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Geeft of stelt de Azure Active Directory (Azure AD) site-identifier weer die overeenkomt met het gevoeligheidslabelbeleid dat het gevoeligheidslabel beschrijft. Lezen/schrijven java.util.UUID.

**Retour:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Geeft of stelt de Azure Active Directory (Azure AD) site-identifier weer die overeenkomt met het gevoeligheidslabelbeleid dat het gevoeligheidslabel beschrijft. Lezen/schrijven java.util.UUID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Geeft aan of het gevoeligheidslabel is ingeschakeld.

**Retour:**
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

**Retour:**
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

Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. Lezen/schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Retour:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Geeft of stelt de toewijzingsmethode voor het gevoeligheidslabel in. Lezen/schrijven [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Geeft de lijst van typen inhoudsmarkering die op een bestand moeten worden toegepast.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)