---
title: WebProxy
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αναπαριστά έναν http web-proxy διακομιστή. Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε αντίτυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα υποβολής. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 495
url: /el/system.net/webproxy/
---
## WebProxy κλάση

Αναπαριστά έναν http web-proxy διακομιστή. Αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα υποβολής. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Λαμβάνει τη διεύθυνση του τρέχοντος διακομιστή proxy. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_BypassList](./get_bypasslist/)() | Λαμβάνει τη λίστα των διευθύνσεων που δεν χρησιμοποιούν τον διακομιστή proxy. |
| **bool** [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Λαμβάνει τιμή που δείχνει αν ο διακομιστής proxy πρέπει να χρησιμοποιηθεί για τοπικές διευθύνσεις. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | Λαμβάνει τα διαπιστευτήρια που αποστέλλονται στον διακομιστή proxy για πιστοποίηση. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Λαμβάνει τιμή που δείχνει αν τα προεπιλεγμένα διαπιστευτήρια πρέπει να αποσταλούν με τα αιτήματα. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebProxy](./)\> [GetDefaultProxy](./getdefaultproxy/)() | Επιστρέφει το proxy που χρησιμοποιεί τις μη-δυναμικές ρυθμίσεις του Internet Explorer. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου [Object.GetHashCode()](../../system/object/gethashcode/) της C#. Διευκολύνει τον κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [GetProxy](./getproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Επιστρέφει το URI μέσω proxy για ένα web αίτημα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης [System.Object.GetType()](../../system/object/gettype/) της C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα αντίτυπο του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή 'is' της C#. |
| virtual **bool** [IsBypassed](./isbypassed/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Ελέγχει αν ο διακομιστής proxy δεν χρησιμοποιείται για το καθορισμένο URI. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης lock() της C#. Καλείτε άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου [Object.MemberwiseClone()](../../system/object/memberwiseclone/) της C#. Διευκολύνει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκατηγορίες. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκατηγορίες. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_Address](./set_address/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Ορίζει τη διεύθυνση του τρέχοντος διακομιστή proxy. |
| void [set_BypassList](./set_bypasslist/)([System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Ορίζει τη λίστα των διευθύνσεων που δεν χρησιμοποιούν τον διακομιστή proxy. |
| void [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(**bool**) | Ορίζει τιμή που δείχνει αν ο διακομιστής proxy πρέπει να χρησιμοποιείται για τοπικές διευθύνσεις. |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Ορίζει τα διαπιστευτήρια που αποστέλλονται στον διακομιστή proxy για πιστοποίηση. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | Ορίζει τιμή που δείχνει αν τα προεπιλεγμένα διαπιστευτήρια πρέπει να αποσταλούν με τα αιτήματα. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου σε αδυνατό δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου [Object.ToString()](../../system/object/tostring/) της C#. Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης lock() της C#. Καλείτε άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύνατων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύνατων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [WebProxy](./webproxy/)() | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **int32_t**) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([String](../../system/string/)) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Δημιουργεί ένα νέο αντικείμενο. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Δημιουργεί ένα νέο αντικείμενο. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IWebProxy](../iwebproxy/)
* Χώρος ονομάτων [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)