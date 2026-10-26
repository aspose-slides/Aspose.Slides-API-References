---
title: SensitivityLabel
second_title: Aspose.Slides für Java API-Referenz
description: Stellt das Sensitivitätskennzeichen von Microsoft Purview Information Protection dar.
type: docs
url: /de/com.aspose.slides/sensitivitylabel/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Stellt das Sensitivitätskennzeichen von Microsoft Purview Information Protection dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getId()](#getId--) | Gibt die ID des Sensitivitätskennzeichens zurück oder setzt sie. |
| [setId(String value)](#setId-java.lang.String-) | Gibt die ID des Sensitivitätskennzeichens zurück oder setzt sie. |
| [getSiteId()](#getSiteId--) | Gibt die Azure Active Directory (Azure AD)-Site-Identifikationsnummer zurück oder setzt sie, die der Richtlinie für das Sensitivitätskennzeichen entspricht, welche das Sensitivitätskennzeichen beschreibt. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Gibt die Azure Active Directory (Azure AD)-Site-Identifikationsnummer zurück oder setzt sie, die der Richtlinie für das Sensitivitätskennzeichen entspricht, welche das Sensitivitätskennzeichen beschreibt. |
| [isEnabled()](#isEnabled--) | Gibt an, ob das Sensitivitätskennzeichen aktiviert ist. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Gibt an, ob das Sensitivitätskennzeichen aktiviert ist. |
| [isRemoved()](#isRemoved--) | Gibt an, ob das Sensitivitätskennzeichen entfernt wurde. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Gibt an, ob das Sensitivitätskennzeichen entfernt wurde. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Gibt die Zuweisungsmethode für das Sensitivitätskennzeichen zurück oder setzt sie. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Gibt die Zuweisungsmethode für das Sensitivitätskennzeichen zurück oder setzt sie. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Gibt die Liste der Arten von Inhaltskennzeichnungen zurück, die auf eine Datei angewendet werden sollen. |
### getId() {#getId--}
```
public final String getId()
```


Gibt die ID des Sensitivitätskennzeichens zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Gibt die ID des Sensitivitätskennzeichens zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Gibt die Azure Active Directory (Azure AD)-Site-Identifikationsnummer zurück oder setzt sie, die der Richtlinie für das Sensitivitätskennzeichen entspricht, welche das Sensitivitätskennzeichen beschreibt. Lesen/Schreiben java.util.UUID.

**Rückgabe:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Gibt die Azure Active Directory (Azure AD)-Site-Identifikationsnummer zurück oder setzt sie, die der Richtlinie für das Sensitivitätskennzeichen entspricht, welche das Sensitivitätskennzeichen beschreibt. Lesen/Schreiben java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Gibt an, ob das Sensitivitätskennzeichen aktiviert ist.

**Rückgabe:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Gibt an, ob das Sensitivitätskennzeichen aktiviert ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Gibt an, ob das Sensitivitätskennzeichen entfernt wurde.

**Rückgabe:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Gibt an, ob das Sensitivitätskennzeichen entfernt wurde.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Gibt die Zuweisungsmethode für das Sensitivitätskennzeichen zurück oder setzt sie. Lesen/Schreiben [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Rückgabe:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Gibt die Zuweisungsmethode für das Sensitivitätskennzeichen zurück oder setzt sie. Lesen/Schreiben [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Gibt die Liste der Arten von Inhaltskennzeichnungen zurück, die auf eine Datei angewendet werden sollen.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Eine Liste von Inhaltstypen [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)