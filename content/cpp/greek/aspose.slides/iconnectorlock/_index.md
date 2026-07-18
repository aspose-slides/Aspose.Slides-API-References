---
title: IConnectorLock
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στον γονέα Connector.
type: docs
weight: 1860
url: /el/aspose.slides/iconnectorlock/
---
## IConnectorLock κλάση

Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στον γονέα [Connector](../connector/).

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
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
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Καθορίζει αν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Καθορίζει αν η αλλαγή των arrowheads απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Καθορίζει αν ένα σχήμα πρέπει να διατηρεί το λόγο διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Επιστρέφει true εάν όλα τα lock-flags είναι απενεργοποιημένα. Μόνο για ανάγνωση **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | Καθορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Καθορίζει αν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Καθορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Καθορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική του C# [Object.GetHashCode()](../../system/object/gethashcode/) μεθόδου. Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του C# τελεστή 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική του C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) μεθόδου. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Καθορίζει αν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Καθορίζει αν η αλλαγή των arrowheads απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Καθορίζει αν ένα σχήμα πρέπει να διατηρεί το λόγο διαστάσεων κατά την αλλαγή μεγέθους. Εγγραφή **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Καθορίζει αν η άμεση αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Καθορίζει αν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | Καθορίζει αν η μετακίνηση αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Καθορίζει αν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Καθορίζει αν η επιλογή αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Καθορίζει αν η αλλαγή τύπου σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Καθορίζει αν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίστε το n'th όρισμα προτύπου σε αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική του C# [Object.ToString()](../../system/object/tostring/) μεθόδου. Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Class [IBaseShapeLock](../ibaseshapelock/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)