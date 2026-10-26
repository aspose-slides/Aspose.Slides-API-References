---
title: SensitivityLabel
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje etykietę wrażliwości z Microsoft Purview Information Protection.
type: docs
url: /pl/com.aspose.slides/sensitivitylabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Reprezentuje etykietę wrażliwości z Microsoft Purview Information Protection.
## Metody

| Metoda | Opis |
| --- | --- |
| [getId()](#getId--) | Zwraca lub ustawia identyfikator etykiety wrażliwości. |
| [setId(String value)](#setId-java.lang.String-) | Zwraca lub ustawia identyfikator etykiety wrażliwości. |
| [getSiteId()](#getSiteId--) | Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. |
| [isEnabled()](#isEnabled--) | Określa, czy etykieta wrażliwości jest włączona. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Określa, czy etykieta wrażliwości jest włączona. |
| [isRemoved()](#isRemoved--) | Określa, czy etykieta wrażliwości została usunięta. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Określa, czy etykieta wrażliwości została usunięta. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Zwraca lub ustawia metodę przypisania etykiety wrażliwości. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Zwraca lub ustawia metodę przypisania etykiety wrażliwości. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Zwraca listę typów oznaczeń treści, które powinny zostać zastosowane do pliku. |
### getId() {#getId--}
```
public final String getId()
```


Zwraca lub ustawia identyfikator etykiety wrażliwości. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Zwraca lub ustawia identyfikator etykiety wrażliwości. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. Odczyt/zapis java.util.UUID.

**Zwraca:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. Odczyt/zapis java.util.UUID.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Określa, czy etykieta wrażliwości jest włączona.

**Zwraca:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Określa, czy etykieta wrażliwości jest włączona.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Określa, czy etykieta wrażliwości została usunięta.

**Zwraca:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Określa, czy etykieta wrażliwości została usunięta.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Zwraca lub ustawia metodę przypisania etykiety wrażliwości. Odczyt/zapis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Zwraca:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Zwraca lub ustawia metodę przypisania etykiety wrażliwości. Odczyt/zapis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Zwraca listę typów oznaczeń treści, które powinny zostać zastosowane do pliku.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Lista typów treści [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)