---
title: AutoShapeLock
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονικό AutoshapeEx.
type: docs
weight: 79
url: /el/aspose.slides/autoshapelock/
---
## AutoShapeLock κλάση

Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στο γονεϊκό AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Καθορίζει αν η αλλαγή των τιμών προσαρμογής είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Καθορίζει αν η αλλαγή των άκρων βέλους είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Καθορίζει αν ένα σχήμα πρέπει να διατηρεί το λόγο διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Επιστρέφει true αν όλα τα lock-flags είναι απενεργοποιημένα. Μόνο ανάγνωση **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Καθορίζει αν η μετακίνηση αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Καθορίζει αν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Καθορίζει αν η επιλογή αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Καθορίζει αν η αλλαγή τύπου ενός σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος είναι απαγορευμένη. Ανάγνωση **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Καθορίζει αν η επεξεργασία κειμένου είναι απαγορευμένη. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος της C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αποτελεί μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικός τελεστής C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος της C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς δημιουργεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς δημιουργεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Καθορίζει αν η αλλαγή των τιμών προσαρμογής είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Καθορίζει αν η αλλαγή των άκρων βέλους είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Καθορίζει αν ένα σχήμα πρέπει να διατηρεί το λόγο διαστάσεων κατά την αλλαγή μεγέθους. Εγγραφή **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Καθορίζει αν η μετακίνηση αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Καθορίζει αν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Καθορίζει αν η επιλογή αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Καθορίζει αν η αλλαγή του τύπου ενός σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος είναι απαγορευμένη. Εγγραφή **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Καθορίζει αν η επεξεργασία κειμένου είναι απαγορευμένη. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδρή δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδρή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος της C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το αδρὸ μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το αδρὸ μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BaseShapeLock](../baseshapelock/)
* Κλάση [IAutoShapeLock](../iautoshapelock/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)