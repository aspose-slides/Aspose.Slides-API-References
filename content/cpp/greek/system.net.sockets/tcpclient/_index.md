---
title: TcpClient
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει έναν πελάτη για τις υπηρεσίες δικτύου TCP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στη στοίβα ή χρησιμοποιώντας operator new, καθώς θα οδηγήσει σε σφάλματα εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 66
url: /el/system.net.sockets/tcpclient/
---
## TcpClient κλάση

Αντιπροσωπεύει έναν πελάτη για τις υπηρεσίες δικτύου TCP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στη στοίβα ή χρησιμοποιώντας operator new, καθώς θα οδηγήσει σε σφάλματα εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class TcpClient : public System::IDisposable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης. |
| void [Close](./close/)() | Κλείνει τη σύνδεση και απελευθερώνει το τρέχον παράδειγμα. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Καθιερώνει μια σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Καθιερώνει μια σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Καθιερώνει μια σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Καθιερώνει μια σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Δεν κάνει τίποτα. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία σύνδεσης. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **int32_t** [get_Available](./get_available/)() | Επιστρέφει τον αριθμό των byte που έχουν ληφθεί και είναι έτοιμα για ανάγνωση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Λαμβάνει το socket. |
| **bool** [get_Connected](./get_connected/)() | Επιστρέφει μια τιμή που υποδεικνύει αν το socket είναι συνδεδεμένο με τον απομακρυσμένο κεντρικό υπολογιστή. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Λαμβάνει μια τιμή που υποδεικνύει αν το τρέχον παράδειγμα επιτρέπει μόνο έναν πελάτη να χρησιμοποιήσει μια θύρα. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Λαμβάνει μια τιμή που υποδεικνύει αν το socket θα καθυστερήσει το κλείσιμο σε μια προσπάθεια αποστολής όλων των εκκρεμών δεδομένων. |
| **bool** [get_NoDelay](./get_nodelay/)() | Λαμβάνει μια τιμή που υποδεικνύει αν το τρέχον παράδειγμα χρησιμοποιεί τον αλγόριθμο Nagle. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Λαμβάνει το μέγεθος της μνήμης buffer που χρησιμοποιείται για λήψη δεδομένων. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Λαμβάνει μια τιμή που υποδεικνύει ένα χρονικό διάστημα μετά το οποίο η λήψη δεδομένων λήγει. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Λαμβάνει το μέγεθος της μνήμης buffer που χρησιμοποιείται για αποστολή δεδομένων. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Λαμβάνει μια τιμή που υποδεικνύει ένα χρονικό διάστημα μετά το οποίο η αποστολή δεδομένων λήγει. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Επιστρέφει τη ροή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα παράδειγμα του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Ορίζει το socket. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει αν το τρέχον παράδειγμα επιτρέπει μόνο έναν πελάτη να χρησιμοποιήσει μια θύρα. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Ορίζει μια τιμή που υποδεικνύει αν το socket θα καθυστερήσει το κλείσιμο σε μια προσπάθεια αποστολής όλων των εκκρεμών δεδομένων. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει αν το τρέχον παράδειγμα χρησιμοποιεί τον αλγόριθμο Nagle. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Ορίζει το μέγεθος της μνήμης buffer που χρησιμοποιείται για λήψη δεδομένων. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Ορίζει μια τιμή που υποδεικνύει ένα χρονικό διάστημα μετά το οποίο η λήψη δεδομένων λήγει. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Ορίζει το μέγεθος της μνήμης buffer που χρησιμοποιείται για αποστολή δεδομένων. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Ορίζει μια τιμή που υποδεικνύει ένα χρονικό διάστημα μετά το οποίο η αποστολή δεδομένων λήγει. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε κοντέινερ σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Δημιουργεί ένα νέο παράδειγμα. |
|  [TcpClient](./tcpclient/)() | Δημιουργεί ένα νέο παράδειγμα. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Δημιουργεί ένα νέο παράδειγμα. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Δημιουργεί ένα νέο παράδειγμα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
| virtual  [~TcpClient](./~tcpclient/)() | Καταστρέφει το τρέχον παράδειγμα. |

## Δείτε επίσης

* Κλάση [IDisposable](../../system/idisposable/)
* Χώρος ονομάτων [System::Net::Sockets](../)
* Βιβλιοθήκη [Aspose.Slides](../../)