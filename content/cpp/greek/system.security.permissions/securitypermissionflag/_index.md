---
title: SecurityPermissionFlag
second_title: Aspose.Slides για C++ API Αναφορά
description: Σημαίες δικαιώματος ασφαλείας.
type: docs
weight: 27
url: /el/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Σημαίες δικαιώματος ασφαλείας.

```cpp
enum class SecurityPermissionFlag
```

### Values

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| NoFlags | 0 | Καμία πρόσβαση. |
| Assertion | 1 | Δηλώστε ότι η άδεια έχει δοθεί. |
| UnmanagedCode | 2 | Κλήση μη διαχειριζόμενου κώδικα. |
| SkipVerification | 4 | Παράλειψη επαλήθευσης κώδικα. |
| Execution | 8 | Εκτέλεση κώδικα. |
| ControlThread | 16 | Εκτέλεση λειτουργιών σε νήματα. |
| ControlEvidence | 32 | Έλεγχος ή τροποποίηση αποδείξεων CLR. |
| ControlPolicy | 64 | Προβολή και αλλαγή πολιτικής. |
| SerializationFormatter | 128 | Σειριοποίηση. |
| ControlDomainPolicy | 256 | Ορισμός πολιτικής τομέα. |
| ControlPrincipal | 512 | Έλεγχος αντικειμένου principal. |
| ControlAppDomain | 1024 | Έλεγχος τομέα εφαρμογής. |
| RemotingConfiguration | 2048 | Διαμόρφωση απομακρυσμένων κλήσεων. |
| Infrastructure | 4096 | Σύνδεση με την υποδομή CLR. |
| BindingRedirects | 8192 | Εκτέλεση ρητής ανακατεύθυνσης δέσμευσης. |
| AllFlags | 16383 | Απεριορισμένο. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Security::Permissions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)