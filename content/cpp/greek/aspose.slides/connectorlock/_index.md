---
title: ConnectorLock
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό Connector.
type: docs
weight: 495
url: /el/aspose.slides/connectorlock/
---
## ConnectorLock κλάση


Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό [Connector](../connector/).

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Προσδιορίζει αν η αλλαγή τιμών προσαρμογής απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Προσδιορίζει αν η αλλαγή κεφαλών βέλους απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Προσδιορίζει αν ένα σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Προσδιορίζει αν η άμεση αλλαγή περιγράμματος αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Προσδιορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Επιστρέφει true εάν όλες οι σημαίες κλειδώματος είναι απενεργοποιημένες. Μόνο προς ανάγνωση **bool**. |
| **bool** [get_PositionMove](./get_positionmove/)() override | Προσδιορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Προσδιορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Προσδιορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Προσδιορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Προσδιορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# `is`. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή C# lock() για κλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Προσδιορίζει αν η αλλαγή τιμών προσαρμογής απαγορεύεται. Εγγραφή **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Προσδιορίζει αν η αλλαγή κεφαλών βέλους απαγορεύεται. Εγγραφή **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Προσδιορίζει αν ένα σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Εγγραφή **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Προσδιορίζει αν η άμεση αλλαγή περιγράμματος αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Προσδιορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Εγγραφή **bool**. |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | Προσδιορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Προσδιορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Προσδιορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Προσδιορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Προσδιορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την εντολή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωση. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BaseShapeLock](../baseshapelock/)
* Κλάση [IConnectorLock](../iconnectorlock/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)