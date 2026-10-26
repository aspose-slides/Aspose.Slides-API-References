---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτικών στοιχείων υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της κύριας διαφάνειας καθώς και όλων των θυγατρικών δεσμευτικών στοιχείων. Τα θυγατρικά δεσμευτικά στοιχεία σημαίνουν ότι τα δεσμευτικά στοιχεία περιέχονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.
type: docs
weight: 4499
url: /el/aspose.slides/masterslideheaderfootermanager/
---
## MasterSlideHeaderFooterManager κλάση

Αντιπροσωπεύει τον διαχειριστή που κρατά τη συμπεριφορά των δεσμευτικών στοιχείων υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της κύριας διαφάνειας καθώς και όλων των θυγατρικών δεσμευτικών στοιχείων. Τα θυγατρικά δεσμευτικά στοιχεία σημαίνουν ότι τα δεσμευτικά στοιχεία περιέχονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

```cpp
class MasterSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::IMasterSlideHeaderFooterManager
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει δεσμευτικό στοιχείο ημερομηνίας-ώρας. Read**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει δεσμευτικό στοιχείο υποσέλιδου. Read **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει δεσμευτικό στοιχείο αριθμού σελίδας. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τον κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφου υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφου υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο δεσμευτικό στοιχείο ημερομηνίας-ώρας της κύριας διαφάνειας και όλα τα θυγατρικά δεσμευτικά στοιχεία ημερομηνίας-ώρας. Τα θυγατρικά δεσμευτικά στοιχεία σημαίνουν ότι τα δεσμευτικά στοιχεία περιέχονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Αλλάζει την ορατότητα του δεσμευτικού στοιχείου ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών στοιχείων ημερομηνίας-ώρας. Τα θυγατρικά δεσμευτικά στοιχεία σημαίνουν ότι τα δεσμευτικά στοιχεία περιέχονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο δεσμευτικό στοιχείο ημερομηνίας-ώρας της διαφάνειας. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Αλλάζει την ορατότητα του δεσμευτικού στοιχείου ημερομηνίας-ώρας της διαφάνειας. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο δεσμευτικό στοιχείο υποσέλιδου της κύριας διαφάνειας και όλα τα θυγατρικά δεσμευτικά στοιχεία υποσέλιδου. Τα θυγατρικά δεσμευτικά στοιχεία σημαίνουν ότι τα δεσμευτικά στοιχεία περιέχονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Αλλάζει την ορατότητα του δεσμευτικού στοιχείου υποσέλιδου της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών στοιχείων υποσέλιδου. Τα θυγατρικά δεσμευτικά στοιχεία σημαίνουν ότι τα δεσμευτικά στοιχεία περιέχονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο δεσμευτικό στοιχείο υποσέλιδου της διαφάνειας. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Αλλάζει την ορατότητα του δεσμευτικού στοιχείου υποσέλιδου της διαφάνειας. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Αλλάζει την ορατότητα του δεσμευτικού στοιχείου αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών στοιχείων αριθμού σελίδας. Τα θυγατρικά δεσμευτικά στοιχεία σημαίνουν ότι τα δεσμευτικά στοιχεία περιέχονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Αλλάζει την ορατότητα του δεσμευτικού στοιχείου αριθμού σελίδας της διαφάνειας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Κλάση [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)