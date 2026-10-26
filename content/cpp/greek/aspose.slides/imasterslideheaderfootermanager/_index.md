---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει διαχειριστή που διατηρεί τη συμπεριφορά του υποσέλιδου κύριας διαφάνειας, των θέσεων κράτησης ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών θέσεων κράτησης. Οι θυγατρικές θέσεις σημαίνουν ότι οι θέσεις βρίσκονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.
type: docs
weight: 2952
url: /el/aspose.slides/imasterslideheaderfootermanager/
---
## IMasterSlideHeaderFooterManager κλάση


Represents manager which holds behavior of the master slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

```cpp
class IMasterSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης ημερομηνίας-ώρας. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης υποσέλιδου. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης αριθμού σελίδας. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλειδωτική δήλωση C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Ορίζει κείμενο στη θέση κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλες τις θυγατρικές θέσεις ημερομηνίας-ώρας. Οι θυγατρικές θέσεις σημαίνουν ότι οι θέσεις βρίσκονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των θυγατρικών θέσεων ημερομηνίας-ώρας. Οι θυγατρικές θέσεις σημαίνουν ότι οι θέσεις βρίσκονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Ορίζει κείμενο στη θέση κράτησης ημερομηνίας-ώρας της διαφάνειας. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας της διαφάνειας. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Ορίζει κείμενο στη θέση κράτησης υποσέλιδου της κύριας διαφάνειας και σε όλες τις θυγατρικές θέσεις υποσέλιδου. Οι θυγατρικές θέσεις σημαίνουν ότι οι θέσεις βρίσκονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου της κύριας διαφάνειας και όλων των θυγατρικών θέσεων υποσέλιδου. Οι θυγατρικές θέσεις σημαίνουν ότι οι θέσεις βρίσκονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Ορίζει κείμενο στη θέση κράτησης υποσέλιδου της διαφάνειας. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου της διαφάνειας. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών θέσεων αριθμού σελίδας. Οι θυγατρικές θέσεις σημαίνουν ότι οι θέσεις βρίσκονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας της διαφάνειας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτης (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)