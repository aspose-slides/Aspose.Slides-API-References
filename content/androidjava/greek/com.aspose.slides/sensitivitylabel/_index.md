---
title: SensitivityLabel
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει την ετικέτα ευαισθησίας από το Microsoft Purview Information Protection.
type: docs
url: /el/com.aspose.slides/sensitivitylabel/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Αντιπροσωπεύει την ετικέτα ευαισθησίας από το Microsoft Purview Information Protection.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getId()](#getId--) | Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. |
| [setId(String value)](#setId-java.lang.String-) | Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. |
| [getSiteId()](#getSiteId--) | Επιστρέφει ή ορίζει το αναγνωριστικό τοπολογίου Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Επιστρέφει ή ορίζει το αναγνωριστικό τοπολογίου Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. |
| [isEnabled()](#isEnabled--) | Υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| [isRemoved()](#isRemoved--) | Υποδεικνύει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Υποδεικνύει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Επιστρέφει τη λίστα τύπων σήμανσης περιεχομένου που πρέπει να εφαρμοστεί σε ένα αρχείο. |
### getId() {#getId--}
```
public final String getId()
```

Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Επιστρέφει ή ορίζει το id της ετικέτας ευαισθησίας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Επιστρέφει ή ορίζει το αναγνωριστικό τοπολογίου Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Επιστρέφει ή ορίζει το αναγνωριστικό τοπολογίου Azure Active Directory (Azure AD) που αντιστοιχεί στην πολιτική ετικέτας ευαισθησίας που περιγράφει την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή java.util.UUID.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη.

**Επιστρέφει:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Υποδεικνύει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί.

**Επιστρέφει:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Υποδεικνύει αν η ετικέτα ευαισθησίας έχει αφαιρεθεί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Επιστρέφει:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Επιστρέφει ή ορίζει τη μέθοδο ανάθεσης για την ετικέτα ευαισθησίας. Ανάγνωση/εγγραφή [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Επιστρέφει τη λίστα τύπων σήμανσης περιεχομένου που πρέπει να εφαρμοστεί σε ένα αρχείο.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Μια λίστα τύπων περιεχομένου [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)