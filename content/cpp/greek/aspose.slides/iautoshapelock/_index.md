---
title: IAutoShapeLock
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό AutoshapeEx.
type: docs
weight: 1379
url: /el/aspose.slides/iautoshapelock/
---
## IAutoShapeLock κλάση

Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Μεθόδοι

| Method | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Καθορίζει αν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Καθορίζει αν η αλλαγή των κεφαλών βέλους απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Καθορίζει αν το σχήμα πρέπει να διατηρήσει την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Διαβάζει **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Επιστρέφει true εάν όλα τα lock-flags είναι απενεργοποιημένα. Μόνο ανάγνωση **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Καθορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Καθορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Καθορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Καθορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Διαβάζει **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Καθορίζει αν η επεξεργασία κειμένου απαγορεύεται. Διαβάζει **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος της C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement κλειδώματος lock() της C#. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος της C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Καθορίζει αν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Γράφει **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Καθορίζει αν η αλλαγή των κεφαλών βέλους απαγορεύεται. Γράφει **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Καθορίζει αν το σχήμα πρέπει να διατηρήσει την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Γράφει **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Γράφει **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Γράφει **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Καθορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Γράφει **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Καθορίζει αν η αλλαγή γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Γράφει **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Καθορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Γράφει **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Καθορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Γράφει **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Γράφει **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Καθορίζει αν η επεξεργασία κειμένου απαγορεύεται. Γράφει **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα πρότυπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδυνατούς τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος της C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement ξεκλειδώματος lock() της C#. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IBaseShapeLock](../ibaseshapelock/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)