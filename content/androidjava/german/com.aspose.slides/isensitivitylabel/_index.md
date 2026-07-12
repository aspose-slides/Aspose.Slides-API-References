---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt das Sensitivitätslabel von Microsoft Purview Information Protection dar.
type: docs
url: /de/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Stellt das Sensitivitätslabel von Microsoft Purview Information Protection dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getId()](#getId--) | Gibt die ID des Sensitivitätslabels zurück oder setzt sie. |
| [setId(String value)](#setId-java.lang.String-) | Gibt die ID des Sensitivitätslabels zurück oder setzt sie. |
| [getSiteId()](#getSiteId--) | Gibt die Azure Active Directory (Azure AD)-Site-Kennung zurück oder setzt sie, die der Richtlinie für das Sensitivitätslabel entspricht, das das Label beschreibt. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Gibt die Azure Active Directory (Azure AD)-Site-Kennung zurück oder setzt sie, die der Richtlinie für das Sensitivitätslabel entspricht, das das Label beschreibt. |
| [isEnabled()](#isEnabled--) | Gibt an, ob das Sensitivitätslabel aktiviert ist. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Gibt an, ob das Sensitivitätslabel aktiviert ist. |
| [isRemoved()](#isRemoved--) | Gibt an, ob das Sensitivitätslabel entfernt wurde. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Gibt an, ob das Sensitivitätslabel entfernt wurde. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Gibt die Zuweisungsmethode für das Sensitivitätslabel zurück oder setzt sie. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Gibt die Zuweisungsmethode für das Sensitivitätslabel zurück oder setzt sie. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Gibt die Liste von Inhaltmarkierungstypen zurück, die auf eine Datei angewendet werden sollen. |
### getId() {#getId--}
```
public abstract String getId()
```


Gibt die ID des Sensitivitätslabels zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Gibt die ID des Sensitivitätslabels zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Gibt die Azure Active Directory (Azure AD)-Site-Kennung zurück oder setzt sie, die der Richtlinie für das Sensitivitätslabel entspricht, das das Label beschreibt. Lesen/Schreiben java.util.UUID.

**Rückgabewert:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Gibt die Azure Active Directory (Azure AD)-Site-Kennung zurück oder setzt sie, die der Richtlinie für das Sensitivitätslabel entspricht, das das Label beschreibt. Lesen/Schreiben java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Gibt an, ob das Sensitivitätslabel aktiviert ist.

**Rückgabewert:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Gibt an, ob das Sensitivitätslabel aktiviert ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Gibt an, ob das Sensitivitätslabel entfernt wurde.

**Rückgabewert:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Gibt an, ob das Sensitivitätslabel entfernt wurde.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Gibt die Zuweisungsmethode für das Sensitivitätslabel zurück oder setzt sie. Lesen/Schreiben [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Rückgabewert:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Gibt die Zuweisungsmethode für das Sensitivitätslabel zurück oder setzt sie. Lesen/Schreiben [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Gibt die Liste von Inhaltmarkierungstypen zurück, die auf eine Datei angewendet werden sollen.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Eine Liste von Inhaltstypen [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)