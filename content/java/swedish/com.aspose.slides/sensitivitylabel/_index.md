---
title: SensitivityLabel
second_title: Aspose.Slides för Java API-referens
description: Representerar känslighetsetiketten från Microsoft Purview Information Protection.
type: docs
url: /sv/com.aspose.slides/sensitivitylabel/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Representerar känslighetsetiketten från Microsoft Purview Information Protection.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getId()](#getId--) | Returnerar eller anger id för känslighetsetiketten. |
| [setId(String value)](#setId-java.lang.String-) | Returnerar eller anger id för känslighetsetiketten. |
| [getSiteId()](#getSiteId--) | Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar känslighetsetikettpolicyn som beskriver känslighetsetiketten. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar känslighetsetikettpolicyn som beskriver känslighetsetiketten. |
| [isEnabled()](#isEnabled--) | Indikerar om känslighetsetiketten är aktiverad. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indikerar om känslighetsetiketten är aktiverad. |
| [isRemoved()](#isRemoved--) | Indikerar om känslighetsetiketten har tagits bort. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indikerar om känslighetsetiketten har tagits bort. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Returnerar eller anger tilldelningsmetod för känslighetsetiketten. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Returnerar eller anger tilldelningsmetod för känslighetsetiketten. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Returnerar listan över typer av innehållsmarkering som bör tillämpas på en fil. |
### getId() {#getId--}
```
public final String getId()
```


Returnerar eller anger id för känslighetsetiketten. Läs/skriv String.

**Returnerar:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Returnerar eller anger id för känslighetsetiketten. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar känslighetsetikettpolicyn som beskriver känslighetsetiketten. Läs/skriv java.util.UUID.

**Returnerar:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Returnerar eller anger Azure Active Directory (Azure AD) sididentifierare som motsvarar känslighetsetikettpolicyn som beskriver känslighetsetiketten. Läs/skriv java.util.UUID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Indikerar om känslighetsetiketten är aktiverad.

**Returnerar:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Indikerar om känslighetsetiketten är aktiverad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Indikerar om känslighetsetiketten har tagits bort.

**Returnerar:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Indikerar om känslighetsetiketten har tagits bort.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Returnerar eller anger tilldelningsmetod för känslighetsetiketten. Läs/skriv [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returnerar:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Returnerar eller anger tilldelningsmetod för känslighetsetiketten. Läs/skriv [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Returnerar listan över typer av innehållsmarkering som bör tillämpas på en fil.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - en lista över innehållstyper [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)