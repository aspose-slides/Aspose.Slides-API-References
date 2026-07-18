---
title: Dns
second_title: Αναφορά API του Aspose.Slides για C++
description: Παρέχει μεθόδους για εργασία με DNS.
type: docs
weight: 105
url: /el/system.net/dns/
---
## Dns κλάση

Παρέχει μεθόδους για εργασία με DNS.

```cpp
class Dns : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostAddresses](./begingethostaddresses/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostByName](./begingethostbyname/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου χρησιμοποιώντας την καθορισμένη διεύθυνση IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginResolve](./beginresolve/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή. |
|  [Dns](./dns/)() | Ο διαγραμμένος προεπιλεγμένος κατασκευαστής. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [EndGetHostAddresses](./endgethostaddresses/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostByName](./endgethostbyname/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostEntry](./endgethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndResolve](./endresolve/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία για τη δημιουργία ενός νέου IPHostEntry-κλάσης αντικειμένου. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [GetHostAddresses](./gethostaddresses/)([String](../../system/string/)) | Επιστρέφει μια συλλογή από διευθύνσεις IP του καθορισμένου ονόματος κεντρικού υπολογιστή ή διεύθυνσης IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([String](../../system/string/)) | Δημιουργεί ένα νέο IPHostEntry-κλάσης αντικείμενο χρησιμοποιώντας την καθορισμένη συμβολοσειρά που αντιπροσωπεύει μια διεύθυνση IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Δημιουργεί ένα νέο IPHostEntry-κλάσης αντικείμενο χρησιμοποιώντας την καθορισμένη διεύθυνση IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByName](./gethostbyname/)([String](../../system/string/)) | Δημιουργεί ένα νέο IPHostEntry-κλάσης αντικείμενο χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([String](../../system/string/)) | Δημιουργεί ένα νέο IPHostEntry-κλάσης αντικείμενο χρησιμοποιώντας την καθορισμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Δημιουργεί ένα νέο IPHostEntry-κλάσης αντικείμενο χρησιμοποιώντας την καθορισμένη διεύθυνση IP. |
| static [String](../../system/string/) [GetHostName](./gethostname/)() | Επιστρέφει το όνομα κεντρικού υπολογιστή του τοπικού μηχανήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευάστης αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [Resolve](./resolve/)([String](../../system/string/)) | Δημιουργεί ένα νέο IPHostEntry-κλάσης αντικείμενο χρησιμοποιώντας το καθορισμένο όνομα κεντρικού υπολογιστή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)