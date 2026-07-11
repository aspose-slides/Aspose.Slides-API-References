---
title: ISensitivityLabel
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά την ετικέτα ευαισθησίας από το Microsoft Purview Information Protection.
type: docs
url: /el/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Αναπαριστά την ετικέτα ευαισθησίας από το Microsoft Purview Information Protection.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getId()](#getId--) | Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. |
| [setId(String value)](#setId-java.lang.String-) | Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. |
| [getSiteId()](#getSiteId--) | Επιστρέφει ή ορίζει το αναγνωριστικό τοποθεσίας του Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Επιστρέφει ή ορίζει το αναγνωριστικό τοποθεσίας του Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. |
| [isEnabled()](#isEnabled--) | Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| [isRemoved()](#isRemoved--) | Δείχνει αν η ετικέτα ευαισθησίας αφαιρέθηκε. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Δείχνει αν η ετικέτα ευαισθησίας αφαιρέθηκε. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Επιστρέφει τη λίστα τύπων σήμανσης περιεχομένου που πρέπει να εφαρμοστούν σε ένα αρχείο. |
### getId() {#getId--}
```
public abstract String getId()
```

Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Επιστρέφει ή ορίζει το αναγνωριστικό τοποθεσίας του Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Επιστρέφει ή ορίζει το αναγνωριστικό τοποθεσίας του Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή java.util.UUID.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη.

**Επιστρέφει:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Δείχνει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Δείχνει αν η ετικέτα ευαισθησίας αφαιρέθηκε.

**Επιστρέφει:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Δείχνει αν η ετικέτα ευαισθησίας αφαιρέθηκε.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Επιστρέφει:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

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