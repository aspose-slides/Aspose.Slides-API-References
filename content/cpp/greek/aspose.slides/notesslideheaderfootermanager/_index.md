---
title: NotesSlideHeaderFooterManager
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά τη διαχειριστική μονάδα που διατηρεί τη συμπεριφορά των συμβόλων κράτησης διαφάνειας σημειώσεων, συμπεριλαμβανομένου του συμβόλου κράτησης κεφαλίδας.
type: docs
weight: 4577
url: /el/aspose.slides/notesslideheaderfootermanager/
---
## NotesSlideHeaderFooterManager κλάση


Represents manager which holds behavior of the notes slide placeholders, including header placeholder.

```cpp
class NotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                      public Aspose::Slides::INotesSlideHeaderFooterManager
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την [Object.Equals](../../system/object/equals/) σημασιολογία της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο κράτησης ημερομηνίας-ώρας. Read**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο κράτησης υποσέλιδου. Read **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο κράτησης κεφαλίδας. Read **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο κράτησης αριθμού σελίδας. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής εκχώρησης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί τη δημιουργία αντιγράφων υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο σύμβολο κράτησης ημερομηνίας-ώρας της διαφάνειας. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Αλλάζει την ορατότητα του συμβόλου κράτησης ημερομηνίας-ώρας της διαφάνειας. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο σύμβολο κράτησης υποσέλιδου της διαφάνειας. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Αλλάζει την ορατότητα του συμβόλου κράτησης υποσέλιδου της διαφάνειας. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | Ορίζει κείμενο στο σύμβολο κράτησης κεφαλίδας της διαφάνειας. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | Αλλάζει την ορατότητα του συμβόλου κράτησης κεφαλίδας της διαφάνειας. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Αλλάζει την ορατότητα του συμβόλου κράτησης αριθμού σελίδας της διαφάνειας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει τη μορφή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* Κλάση [INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)