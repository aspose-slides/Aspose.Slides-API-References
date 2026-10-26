---
title: PictureFrameLock
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό PictureFrame.
type: docs
weight: 4746
url: /el/aspose.slides/pictureframelock/
---
## PictureFrameLock κλάση

Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Καθορίζει αν η αλλαγή τιμών προσαρμογής απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Καθορίζει αν η αλλαγή των άκρων βέλους απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Καθορίζει αν ένα σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Καθορίζει αν η περικοπή εικόνας απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Επιστρέφει true εάν όλα τα flags κλειδώματος είναι απενεργοποιημένα. Μόνο για ανάγνωση **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Καθορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Καθορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Καθορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Καθορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Ανάλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Κλήστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Διευκολύνει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Καθορίζει αν η αλλαγή τιμών προσαρμογής απαγορεύεται. Εγγραφή **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Καθορίζει αν η αλλαγή των άκρων βέλους απαγορεύεται. Εγγραφή **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Καθορίζει αν ένα σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Εγγραφή **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Καθορίζει αν η περικοπή εικόνας απαγορεύεται. Εγγραφή **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Εγγραφή **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Καθορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Καθορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Καθορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Καθορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Εγγραφή **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα του προτύπου ως αδύνατο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη κατάσταση. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Κλήστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BaseShapeLock](../baseshapelock/)
* Κλάση [IPictureFrameLock](../ipictureframelock/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)