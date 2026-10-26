---
title: IPAddress
second_title: Αναφορά API Aspose.Slides για C++
description: "Αναπαριστά τη διεύθυνση IP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα περικλείετε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 326
url: /el/system.net/ipaddress/
---
## IPAddress κλάση


Αντιπροσωπεύει τη διεύθυνση IP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα περικλείετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class IPAddress : public System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση τύπου κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση τύπου κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Επιστρέφει την οικογένεια διεύθυνσης. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Επιστρέφει τιμή που υποδεικνύει αν η διεύθυνση είναι IPv4 και έχει αντιστοιχιστεί σε διεύθυνση IPv6. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Επιστρέφει τιμή που υποδεικνύει αν η διεύθυνση είναι IPv6 link-local. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Επιστρέφει τιμή που υποδεικνύει αν η διεύθυνση είναι παγκόσμια διεύθυνση multicast IPv6. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Επιστρέφει τιμή που υποδεικνύει αν η διεύθυνση είναι IPv6 site-local. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Επιστρέφει τιμή που υποδεικνύει αν η διεύσταση είναι IPv6 Teredo. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Λαμβάνει το αναγνωριστικό εμβέλειας της διεύθυνσης IPv6. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Επιστρέφει έναν πίνακα byte της διεύθυνσης IP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Επιστρέφει δείκτη στην υλοποίηση. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Μετατρέπει τη συγκεκριμένη σειρά byte του κεντρικού συστήματος στη αντίστοιχη σειρά byte του δικτύου. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Μετατρέπει τη συγκεκριμένη σειρά byte του κεντρικού συστήματος στη αντίστοιχη σειρά byte του δικτύου. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Μετατρέπει τη συγκεκριμένη σειρά byte του κεντρικού συστήματος στη αντίστοιχη σειρά byte του δικτύου. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Δημιουργεί μια νέα παρουσία. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Δημιουργεί μια νέα παρουσία. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Δημιουργεί μια νέα παρουσία. |
|  [IPAddress](./ipaddress/)() | Δημιουργεί μια νέα παρουσία. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Επιστρέφει τιμή που υποδεικνύει αν η συγκεκριμένη διεύθυνση είναι διεύθυνση loopback. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της εντολής C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Χαρτογραφεί τη διεύθυνση σε διεύθυνση IPv4. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Χαρτογραφεί τη διεύθυνση σε διεύθυνση IPv6. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Μετατρέπει τη συγκεκριμένη σειρά byte του δικτύου στην αντίστοιχη σειρά byte του κεντρικού συστήματος. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Μετατρέπει τη συγκεκριμένη σειρά byte του δικτύου στην αντίστοιχη σειρά byte του κεντρικού συστήματος. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Μετατρέπει τη συγκεκριμένη σειρά byte του δικτύου στην αντίστοιχη σειρά byte του κεντρικού συστήματος. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει δημιουργία αντιγράφου σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστή ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει δημιουργία αντιγράφου σε υποκλάσεις. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Μετατρέπει μια δοθείσα συμβολοσειρά σε παρουσία της κλάσης [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Ορίζει το αναγνωριστικό εμβέλειας της διεύθυνσης IPv6. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Ορίζει δείκτη στην υλοποίηση. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'ο όρισμα πρότυπου ως αδυναμικό δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Προσπαθεί να μετατρέψει μια δοθείσα συμβολοσειρά σε παρουσία της κλάσης [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της εντολής C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [Any](./any/) | Η διεύθυνση IPv4 που υποδεικνύει αν ο διακομιστής πρέπει να ακούει σε όλα τα δικτυακά interfaces. |
| static [Broadcast](./broadcast/) | Η διεύθυνση broadcast IPv4. |
| static [IPv6Any](./ipv6any/) | Η διεύθυνση IPv6 που υποδεικνύει αν ο διακομιστής πρέπει να ακούει σε όλα τα δικτυακά interfaces. |
| static [IPv6Loopback](./ipv6loopback/) | Η διεύθυνση loopback IPv6. |
| static [IPv6None](./ipv6none/) | Η διεύθυνση IPv6 που υποδεικνύει αν ο διακομιστής δεν πρέπει να ακούει σε κανένα δικτυακό interface. |
| static [Loopback](./loopback/) | Η διεύθυνση loopback IPv4. |
| static [None](./none/) | Η διεύθυνση IPv4 που υποδεικνύει αν ο διακομιστής δεν πρέπει να ακούει σε κανένα δικτυακό interface. |
## Ορισμοί τύπων

| Typedef | Περιγραφή |
| --- | --- |
| [ImplPtr](./implptr/) | Δείκτης προς τον τύπο υλοποίησης. |
## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)