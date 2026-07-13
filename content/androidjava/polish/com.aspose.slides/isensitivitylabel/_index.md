---
title: ISensitivityLabel
second_title: Aspose.Slides dla Androida przez odwołanie API Javy
description: Reprezentuje etykietę wrażliwości z Microsoft Purview Information Protection.
type: docs
url: /pl/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Reprezentuje etykietę wrażliwości z Microsoft Purview Information Protection.
## Metody

| Metoda | Opis |
| --- | --- |
| [getId()](#getId--) | Zwraca lub ustawia id etykiety wrażliwości. |
| [setId(String value)](#setId-java.lang.String-) | Zwraca lub ustawia id etykiety wrażliwości. |
| [getSiteId()](#getSiteId--) | Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. |
| [isEnabled()](#isEnabled--) | Wskazuje, czy etykieta wrażliwości jest włączona. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Wskazuje, czy etykieta wrażliwości jest włączona. |
| [isRemoved()](#isRemoved--) | Wskazuje, czy etykieta wrażliwości została usunięta. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Wskazuje, czy etykieta wrażliwości została usunięta. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Zwraca lub ustawia metodę przypisania etykiety wrażliwości. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Zwraca lub ustawia metodę przypisania etykiety wrażliwości. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Zwraca listę typów oznaczania treści, które powinny zostać zastosowane do pliku. |
### getId() {#getId--}
```
public abstract String getId()
```

Zwraca lub ustawia id etykiety wrażliwości. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Zwraca lub ustawia id etykiety wrażliwości. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. Odczyt/zapis java.util.UUID.

**Zwraca:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety wrażliwości opisującej etykietę wrażliwości. Odczyt/zapis java.util.UUID.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Wskazuje, czy etykieta wrażliwości jest włączona.

**Zwraca:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Wskazuje, czy etykieta wrażliwości jest włączona.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Wskazuje, czy etykieta wrażliwości została usunięta.

**Zwraca:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Wskazuje, czy etykieta wrażliwości została usunięta.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Zwraca lub ustawia metodę przypisania etykiety wrażliwości. Odczyt/zapis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Zwraca:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Zwraca lub ustawia metodę przypisania etykiety wrażliwości. Odczyt/zapis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Zwraca listę typów oznaczania treści, które powinny zostać zastosowane do pliku.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Lista typów treści [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)