---
title: IGroupShapeLock
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό GroupShape.
type: docs
weight: 2497
url: /el/aspose.slides/igroupshapelock/
---
## IGroupShapeLock κλάση

Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό [GroupShape](../groupshape/).

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την C# [Object.Equals](../../system/object/equals/) σημασιολογία. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση σημείου αιτιότητας τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση σημείου αιτιότητας τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Για εσωτερική χρήση μόνο. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Καθορίζει αν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα είναι απαγορευμένη. Ανάγνωση **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Επιστρέφει true εάν όλες οι σημαίες κλειδωματος είναι απενεργοποιημένες. Μόνο-ανάγωση **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Καθορίζει αν η μετακίνηση αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Καθορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Καθορίζει αν η επιλογή αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | Καθορίζει αν ο διαχωρισμός αυτού του σχήματος ομάδας είναι απαγορευμένος. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της C# [Object.GetHashCode()](../../system/object/gethashcode/) μεθόδου. Ενεργοποιεί την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της C# [System.Object.GetType()](../../system/object/gettype/) κλήσης. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αντίστοιχο του C# τελεστή 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την δήλωση κλειδώματος C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική με τη μέθοδο C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστή ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Καθορίζει αν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Εγγραφή **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα είναι απαγορευμένη. Εγγραφή **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Καθορίζει αν η μετακίνηση αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Καθορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Καθορίζει αν η επιλογή αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | Καθορίζει αν ο διαχωρισμός αυτού του σχήματος ομάδας είναι απαγορευμένος. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυνατή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική με τη μέθοδο C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εκδέσμευση της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IBaseShapeLock](../ibaseshapelock/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)