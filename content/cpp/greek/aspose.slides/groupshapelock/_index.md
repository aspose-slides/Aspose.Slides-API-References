---
title: GroupShapeLock
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στον γονέα GroupShape.
type: docs
weight: 1210
url: /el/aspose.slides/groupshapelock/
---
## GroupShapeLock κλάση

Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στον γονέα [GroupShape](../groupshape/).

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Καθορίζει εάν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την κλιμάκωση. Ανάγνωση **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Επιστρέφει true εάν όλα τα lock-flags είναι απενεργοποιημένα. Μόνο για ανάγνωση **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Καθορίζει εάν η μετακίνηση αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Καθορίζει εάν η αλλαγή γωνίας περιστροφής αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Καθορίζει εάν η επιλογή αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | Καθορίζει εάν ο διαχωρισμός αυτού του groupshape είναι απαγορευμένος. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράψει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τέλεσης ανάθεσης. Δεν αντιγράψει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Καθορίζει εάν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την κλιμάκωση. Εγγραφή **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Καθορίζει εάν η μετακίνηση αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Καθορίζει εάν η αλλαγή γωνίας περιστροφής αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Καθορίζει εάν η επιλογή αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | Καθορίζει εάν ο διαχωρισμός αυτού του groupshape είναι απαγορευμένος. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποκλειστική εντολή C# lock() για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BaseShapeLock](../baseshapelock/)
* Κλάση [IGroupShapeLock](../igroupshapelock/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)