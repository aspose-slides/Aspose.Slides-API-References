---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides για C++ Ανάγνωση API
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά του υποσέλιδου της διαφάνειας διάταξης, των αντικειμένων κράτησης θέσης ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών αντικειμένων κράτησης θέσης. Τα θυγατρικά αντικείμενα κράτησης θέσης σημαίνουν ότι τα αντικείμενα κράτησης θέσης περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνιες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.
type: docs
weight: 2666
url: /el/aspose.slides/ilayoutslideheaderfootermanager/
---
## ILayoutSlideHeaderFooterManager κλάση

Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

```cpp
class ILayoutSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με το NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει αντικείμενο κράτησης θέσης ημερομηνίας-ώρας. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει αντικείμενο κράτησης θέσης υποσέλιδου. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει αντικείμενο κράτησης θέσης αριθμού σελίδας. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement κλειδώματος C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση του string και του nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Ορίζει κείμενο στο αντικείμενο κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας διάταξης και σε όλα τα θυγατρικά αντικείμενα κράτησης θέσης ημερομηνίας-ώρας. Τα θυγατρικά αντικείμενα κράτησης θέσης σημαίνουν ότι τα αντικείμενα κράτησης θέσης περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας διάταξης και όλων των θυγατρικών αντικειμένων κράτησης θέσης ημερομηνίας-ώρας. Τα θυγατρικά αντικείμενα κράτησης θέσης σημαίνουν ότι τα αντικείμενα κράτησης θέσης περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Ορίζει κείμενο στο αντικείμενο κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Ορίζει κείμενο στο αντικείμενο κράτησης θέσης υποσέλιδου της διαφάνειας διάταξης και σε όλα τα θυγατρικά αντικείμενα κράτησης θέσης υποσέλιδου. Τα θυγατρικά αντικείμενα κράτησης θέσης σημαίνουν ότι τα αντικείμενα κράτησης θέσης περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης υποσέλιδου της διαφάνειας διάταξης και όλων των θυγατρικών αντικειμένων κράτησης θέσης υποσέλιδου. Τα θυγατρικά αντικείμενα κράτησης θέσης σημαίνουν ότι τα αντικείμενα κράτησης θέσης περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Ορίζει κείμενο στο αντικείμενο κράτησης θέσης υποσέλιδου της διαφάνειας. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης υποσέλιδου της διαφάνειας. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης αριθμού σελίδας της διαφάνειας διάταξης και όλων των θυγατρικών αντικειμένων κράτησης θέσης αριθμού σελίδας. Τα θυγατρικά αντικείμενα κράτησης θέσης σημαίνουν ότι τα αντικείμενα κράτησης θέσης περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης αριθμού σελίδας της διαφάνειας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'ο όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement ξεκλειδώματος C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)