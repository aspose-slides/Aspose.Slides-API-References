---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides για την τεκμηρίωση API του C++
description: Αντιπροσωπεύει τον διαχειριστή που κατέχει τη συμπεριφορά του υποσέλιδου, της θέσης κράτησης ημερομηνίας-ώρας, των θέσεων κράτησης αριθμού σελίδας και όλων των θυγατρικών θέσεων κράτησης της κύριας διαφάνειας σημειώσεων. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.
type: docs
weight: 4460
url: /el/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager κλάση


Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending notes slides. Depending notes slides use and depend on master notes slide.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης ημερομηνίας-ώρας. Ανάγνωση**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης υποσέλιδου. Ανάγνωση **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης κεφαλίδας. Ανάγνωση **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης αριθμού σελίδας. Ανάγνωση**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Σύγκριση αναφοράς αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Ορίζει το κείμενο στην θέση κράτησης ημερομηνίας-ώρας του κύριου διαφάνειας και σε όλες τις θυγατρικές θέσεις κράτησης ημερομηνίας-ώρας. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια σημειώσεων. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας του κύριου διαφάνειας και όλων των θυγατρικών θέσεων κράτησης ημερομηνίας-ώρας. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια σημειώσεων. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Ορίζει το κείμενο στη θέση κράτησης ημερομηνίας-ώρας της διαφάνειας. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας της διαφάνειας. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Ορίζει το κείμενο στη θέση κράτησης υποσέλιδου του κύριου διαφάνειας και σε όλες τις θυγατρικές θέσεις κράτησης υποσέλιδου. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια σημειώσεων. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου του κύριου διαφάνειας και όλων των θυγατρικών θέσεων κράτησης υποσέλιδου. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια σημειώσεων. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Ορίζει το κείμενο στη θέση κράτησης υποσέλιδου της διαφάνειας. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου της διαφάνειας. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | Ορίζει το κείμενο στη θέση κράτησης κεφαλίδας του κύριου σημειώματος διαφάνειας και σε όλες τις θυγατρικές θέσεις κράτησης κεφαλίδας. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια σημειώσεων. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης κεφαλίδας του κύριου σημειώματος διαφάνειας και όλων των θυγατρικών θέσεων κράτησης κεφαλίδας. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια σημειώσεων. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | Ορίζει το κείμενο στη θέση κράτησης κεφαλίδας της διαφάνειας. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης κεφαλίδας της διαφάνειας. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας του κύριου διαφάνειας και όλων των θυγατρικών θέσεων κράτησης αριθμού σελίδας. Οι θυγατρικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια σημειώσεων. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας της διαφάνειας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν θα πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν θα πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει το C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την αποδέσμευση της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφορών. Δεν θα πρέπει να καλείται απευθεία· αντίθετα, χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφορών. Δεν θα πρέπει να καλείται απευθεία· αντίθετα, χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* Κλάση [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)