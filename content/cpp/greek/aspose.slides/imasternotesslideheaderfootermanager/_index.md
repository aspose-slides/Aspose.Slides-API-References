---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά του υποσέλιδου της κύριας διαφάνειας σημειώσεων, των αντικαταστατών ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών αντικαταστατών. Οι θυγατρικοί αντικαταστάτες σημαίνουν ότι οι αντικαταστάτες περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.
type: docs
weight: 2900
url: /el/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager κλάση

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά του υποσέλιδου των κύριων διαφανειών σημειώσεων, των αντικαταστατών ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών αντικαταστατών. Οι θυγατρικοί αντικαταστάτες σημαίνουν ότι οι αντικαταστάτες περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη συγκριτική κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη συγκριτική κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει αντικαταστάτης ημερομηνίας-ώρας. Ανάγνωση**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει αντικαταστάτης υποσημείου. Ανάγνωση **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει αντικαταστάτης κεφαλίδας. Ανάγνωση **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει αντικαταστάτης αριθμού σελίδας. Ανάγνωση**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογικός του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το άνοιγμα κλειδώματος της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Ορίζει κείμενο στο αντικαταστάτη ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και σε όλους τους θυγατρικούς αντικαταστάτες ημερομηνίας-ώρας. Οι θυγατρικοί αντικαταστάτες σημαίνουν ότι οι αντικαταστάτες περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών αντικαταστατών ημερομηνίας-ώρας. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Ορίζει κείμενο στον αντικαταστάτη ημερομηνίας-ώρας της διαφάνειας. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη ημερομηνίας-ώρας της διαφάνειας. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Ορίζει κείμενο στον αντικαταστάτη υποσημείου της κύριας διαφάνειας σημειώσεων και σε όλους τους θυγατρικούς αντικαταστάτες υποσημείου. Οι θυγατρικοί αντικαταστάτες σημαίνουν ότι οι αντικαταστάτες περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη υποσημείου της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών αντικαταστατών υποσημείου. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Ορίζει κείμενο στον αντικαταστάτη υποσημείου της διαφάνειας. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη υποσημείου της διαφάνειας. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | Ορίζει κείμενο στον αντικαταστάτη κεφαλίδας της κύριας διαφάνειας σημειώσεων και σε όλους τους θυγατρικούς αντικαταστάτες κεφαλίδας. Οι θυγατρικοί αντικαταστάτες σημαίνουν ότι οι αντικαταστάτες περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη κεφαλίδας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών αντικαταστατών κεφαλίδας. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | Ορίζει κείμενο στον αντικαταστάτη κεφαλίδας της διαφάνειας. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη κεφαλίδας της διαφάνειας. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη αριθμού σελίδας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών αντικαταστατών αριθμού σελίδας. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Αλλάζει την ορατότητα του αντικαταστάτη αριθμού σελίδας της διαφάνειας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)