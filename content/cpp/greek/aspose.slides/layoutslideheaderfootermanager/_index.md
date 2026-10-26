---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides για την αναφορά API του C++
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των στοιχείων υποδοχής υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών στοιχείων υποδοχής της διάταξης διαφάνειας. Τα θυγατρικά στοιχεία υποδοχής σημαίνουν ότι τα στοιχεία υποδοχής περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.
type: docs
weight: 4317
url: /el/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager κλάση


Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εμείνεται σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εμείνεται σύγκριση κινητής υποδιαστολής διπλής ακρίβειας στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει αντίστοιχο ημερομηνίας-ώρας. Ανάγνωση**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδαχτυλίδι υποσέλιδου. Ανάγνωση **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδαχτυλίδι αριθμού σελίδας. Ανάγνωση**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της εντολής C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικότητα του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικότητα του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον καταμετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο υπόδειγμα ημερομηνίας-ώρας της διαφάνειας διάταξης και σε όλα τα θυγατρικά υποδείγματα ημερομηνίας-ώρας. Τα θυγατρικά υποδείγματα σημαίνουν ότι τα υποδείγματα είναι περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Αλλάζει την ορατότητα του υποδείγματος ημερομηνίας-ώρας της διαφάνειας διάταξης και όλων των θυγατρικών υποδειγμάτων ημερομηνίας-ώρας. Τα θυγατρικά υποδείγματα σημαίνουν ότι τα υποδείγματα είναι περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο υπόδειγμα ημερομηνίας-ώρας της διαφάνειας. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Αλλάζει την ορατότητα του υποδείγματος ημερομηνίας-ώρας της διαφάνειας. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο υπόδειγμα υποσέλιδου της διαφάνειας διάταξης και σε όλα τα θυγατρικά υποδείγματα υποσέλιδου. Τα θυγατρικά υποδείγματα σημαίνουν ότι τα υποδείγματα είναι περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Αλλάζει την ορατότητα του υποδείγματος υποσέλιδου της διαφάνειας διάταξης και όλων των θυγατρικών υποδειγμάτων υποσέλιδου. Τα θυγατρικά υποδείγματα σημαίνουν ότι τα υποδείγματα είναι περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο υπόδειγμα υποσέλιδου της διαφάνειας. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Αλλάζει την ορατότητα του υποδείγματος υποσέλιδου της διαφάνειας. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Αλλάζει την ορατότητα του υποδείγματος αριθμού σελίδας της διαφάνειας διάταξης και όλων των θυγατρικών υποδειγμάτων αριθμού σελίδας. Τα θυγατρικά υποδείγματα σημαίνουν ότι τα υποδείγματα είναι περιέχονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Αλλάζει την ορατότητα του υποδείγματος αριθμού σελίδας της διαφάνειας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα προτύπου σε αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δομή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Κλάση [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)