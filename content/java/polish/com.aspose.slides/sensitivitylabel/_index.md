---
title: SensitivityLabel
second_title: Odwołanie API Aspose.Slides dla Java
description: Reprezentuje etykietę poufności z Microsoft Purview Information Protection.
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

Reprezentuje etykietę poufności z Microsoft Purview Information Protection.

## Metody

| Metoda | Opis |
| --- | --- |
| [getId()](#getId--) | Zwraca lub ustawia identyfikator etykiety poufności. |
| [setId(String value)](#setId-java.lang.String-) | Zwraca lub ustawia identyfikator etykiety poufności. |
| [getSiteId()](#getSiteId--) | Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety poufności opisującej etykietę poufności. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety poufności opisującej etykietę poufności. |
| [isEnabled()](#isEnabled--) | Wskazuje, czy etykieta poufności jest włączona. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Wskazuje, czy etykieta poufności jest włączona. |
| [isRemoved()](#isRemoved--) | Wskazuje, czy etykieta poufności została usunięta. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Wskazuje, czy etykieta poufności została usunięta. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Zwraca lub ustawia metodę przypisania etykiety poufności. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Zwraca lub ustawia metodę przypisania etykiety poufności. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Zwraca listę typów znakowania treści, które powinny być zastosowane do pliku. |
### getId() {#getId--}
```
public final String getId()
```

Zwraca lub ustawia identyfikator etykiety poufności. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Zwraca lub ustawia identyfikator etykiety poufności. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety poufności opisującej etykietę poufności. Odczyt/zapis java.util.UUID.

**Zwraca:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Zwraca lub ustawia identyfikator witryny Azure Active Directory (Azure AD) odpowiadający polityce etykiety poufności opisującej etykietę poufności. Odczyt/zapis java.util.UUID.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Wskazuje, czy etykieta poufności jest włączona.

**Zwraca:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Wskazuje, czy etykieta poufności jest włączona.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Wskazuje, czy etykieta poufności została usunięta.

**Zwraca:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Wskazuje, czy etykieta poufności została usunięta.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Zwraca lub ustawia metodę przypisania etykiety poufności. Odczyt/zapis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Zwraca:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Zwraca lub ustawia metodę przypisania etykiety poufności. Odczyt/zapis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Zwraca listę typów znakowania treści, które powinny być zastosowane do pliku.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Lista typów treści [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)