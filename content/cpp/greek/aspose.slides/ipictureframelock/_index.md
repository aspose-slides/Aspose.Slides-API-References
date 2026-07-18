---
title: IPictureFrameLock
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στον γονέα PictureFrameEx.
type: docs
weight: 3264
url: /el/aspose.slides/ipictureframelock/
---
## IPictureFrameLock κλάση

Determines which operations are disabled on the parent PictureFrameEx.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Υποστηρίζει σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Υποστηρίζει σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Καθορίζει εάν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Καθορίζει εάν η αλλαγή των κεφαλών βέλους απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Καθορίζει εάν ένα σχήμα πρέπει να διατηρήσει την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Καθορίζει εάν η περικοπή εικόνας απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Καθορίζει εάν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Επιστρέφει true εάν όλες οι σημαίες κλειδώματος είναι απενεργοποιημένες. Μόνο ανάγνωση **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Καθορίζει εάν η μετακίνηση αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Καθορίζει εάν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Καθορίζει εάν η επιλογή αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Καθορίζει εάν η αλλαγή τύπου σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement κλειδώματος C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει ως αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Καθορίζει εάν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Καθορίζει εάν η αλλαγή των κεφαλών βέλους απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Καθορίζει εάν ένα σχήμα πρέπει να διατηρήσει την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Εγγραφή **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Καθορίζει εάν η περικοπή εικόνας απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Καθορίζει εάν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Καθορίζει εάν η μετακίνηση αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Καθορίζει εάν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Καθορίζει εάν η επιλογή αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Καθορίζει εάν η αλλαγή τύπου σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement ξεκλειδώματος C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IBaseShapeLock](../ibaseshapelock/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)