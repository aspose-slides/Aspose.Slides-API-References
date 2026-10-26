---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar känslighetsetiketten från Microsoft Purview Information Protection.
type: docs
url: /sv/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Representerar känslighetsetiketten från Microsoft Purview Information Protection.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getId()](#getId--) | Returnerar eller anger id för känslighetsetikett. |
| [setId(String value)](#setId-java.lang.String-) | Returnerar eller anger id för känslighetsetikett. |
| [getSiteId()](#getSiteId--) | Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar säkerhetsetikettspolicyn som beskriver känslighetsetiketten. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar säkerhetsetikettspolicyn som beskriver känslighetsetiketten. |
| [isEnabled()](#isEnabled--) | Anger om känslighetsetiketten är aktiverad. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Anger om känslighetsetiketten är aktiverad. |
| [isRemoved()](#isRemoved--) | Anger om känslighetsetiketten har tagits bort. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Anger om känslighetsetiketten har tagits bort. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Returnerar eller anger tilldelningsmetoden för känslighetsetiketten. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Returnerar eller anger tilldelningsmetoden för känslighetsetiketten. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Returnerar listan över typer av innehållsmärkning som ska tillämpas på en fil. |
### getId() {#getId--}
```
public abstract String getId()
```


Returnerar eller anger id för känslighetsetikett. Läs/skriv String.

**Returnerar:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Returnerar eller anger id för känslighetsetikett. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar säkerhetsetikettspolicyn som beskriver känslighetsetiketten. Läs/skriv java.util.UUID.

**Returnerar:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar säkerhetsetikettspolicyn som beskriver känslighetsetiketten. Läs/skriv java.util.UUID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Anger om känslighetsetiketten är aktiverad.

**Returnerar:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Anger om känslighetsetiketten är aktiverad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Anger om känslighetsetiketten har tagits bort.

**Returnerar:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Anger om känslighetsetiketten har tagits bort.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Returnerar eller anger tilldelningsmetoden för känslighetsetiketten. Läs/skriv [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returnerar:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Returnerar eller anger tilldelningsmetoden för känslighetsetiketten. Läs/skriv [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Returnerar listan över typer av innehållsmärkning som ska tillämpas på en fil.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - En lista över innehållstyper [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)