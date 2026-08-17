---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Αντιπροσωπεύει την ετικέτα ευαισθησίας από το Microsoft Purview Information Protection.
type: docs
url: /el/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Αντιπροσωπεύει την ετικέτα ευαισθησίας από το Microsoft Purview Information Protection.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getId()](#getId--) | Επιστρέφει ή ορίζει το αναγνωριστικό της ετικέτας ευαισθησίας. |
| [setId(String value)](#setId-java.lang.String-) | Επιστρέφει ή ορίζει το αναγνωριστικό της ετικέτας ευαισθησίας. |
| [getSiteId()](#getSiteId--) | Επιστρέφει ή ορίζει το αναγνωριστικό της τοποθεσίας Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Επιστρέφει ή ορίζει το αναγνωριστικό της τοποθεσίας Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα. |
| [isEnabled()](#isEnabled--) | Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργή. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργή. |
| [isRemoved()](#isRemoved--) | Δείχνει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Δείχνει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Επιστρέφει ή ορίζει τη μέθοδο εκχώρησης για την ετικέτα ευαισθησίας. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Επιστρέφει ή ορίζει τη μέθοδο εκχώρησης για την ετικέτα ευαισθησίας. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Επιστρέφει τη λίστα τύπων σήμανσης περιεχομένου που πρέπει να εφαρμοστούν σε ένα αρχείο. |
### getId() {#getId--}
```
public abstract String getId()
```

Επιστρέφει ή ορίζει το αναγνωριστικό της ετικέτας ευαισθησίας. Read/write String.

**Επιστρέφει:**  
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Επιστρέφει ή ορίζει το αναγνωριστικό της ετικέτας ευαισθησίας. Read/write String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Επιστρέφει ή ορίζει το αναγνωριστικό της τοποθεσίας Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα. Read/write java.util.UUID.

**Επιστρέφει:**  
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Επιστρέφει ή ορίζει το αναγνωριστικό της τοποθεσίας Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα. Read/write java.util.UUID.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργή.

**Επιστρέφει:**  
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Δείχνει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί.

**Επιστρέφει:**  
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Δείχνει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Επιστρέφει ή ορίζει τη μέθοδο εκχώρησης για την ετικέτα ευαισθησίας. Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Επιστρέφει:**  
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Επιστρέφει ή ορίζει τη μέθοδο εκχώρησης για την ετικέτα ευαισθησίας. Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Επιστρέφει τη λίστα τύπων σήμανσης περιεχομένου που πρέπει να εφαρμοστούν σε ένα αρχείο.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Μια λίστα τύπων περιεχομένου [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)