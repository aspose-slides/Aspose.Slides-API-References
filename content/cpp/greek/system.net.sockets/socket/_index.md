---
title: Socket
second_title: Aspose.Slides για C++ API Αναφορά
description: Η κλάση Socket υλοποιεί τη διεπαφή Berkeley sockets.
type: docs
weight: 53
url: /el/system.net.sockets/socket/
---
## Κλάση Socket


Η κλάση [Socket](./) υλοποιεί την διεπαφή Berkeley sockets.

```cpp
class Socket : public System::IDisposable
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | Δημιουργεί ένα νέο socket για τη νεοδημιουργημένη σύνδεση. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Εκκινεί μια ασύγχρονη λειτουργία σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Εκκινεί μια ασύγχρονη λειτουργία σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Εκκινεί μια ασύγχρονη λειτουργία σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Εκκινεί μια ασύγχρονη λειτουργία σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Εκκινεί μια ασύγχρονη λειτουργία εγγραφής. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Εκκινεί μια ασύγχρονη λειτουργία αποστολής. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Δεσμεύει το socket στο καθορισμένο τοπικό endpoint. |
| void [Close](./close/)() | Κλείνει τη σύνδεση του socket. |
| void [Close](./close/)(int) | Κλείνει τη σύνδεση του socket με το καθορισμένο χρονικό όριο για να επιτρέψει την αποστολή των ουρά δεδομένων. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Καθιερώνει μια σύνδεση με το καθορισμένο απομακρυσμένο endpoint. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Καθιερώνει μια σύνδεση με το καθορισμένο απομακρυσμένο endpoint. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Καθιερώνει μια σύνδεση με το καθορισμένο απομακρυσμένο endpoint. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Καθιερώνει μια σύνδεση με το καθορισμένο απομακρυσμένο endpoint. |
| void [Dispose](./dispose/)() override | Δεν κάνει τίποτα. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία σύνδεσης. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία λήψης. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία λήψης. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία αποστολής. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία αποστολής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμη και με NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Επιστρέφει την οικογένεια διευθύνσεων. |
| **int32_t** [get_Available](./get_available/)() | Λαμβάνει τον αριθμό των bytes που ελήφθησαν από το δίκτυο και είναι διαθέσιμοι για ανάγνωση. |
| **bool** [get_Blocking](./get_blocking/)() | Λαμβάνει μια τιμή που δείχνει αν το socket βρίσκεται σε λειτουργία φραγής. |
| **bool** [get_Connected](./get_connected/)() | Επιστρέφει τιμή που δείχνει αν το socket είναι συνδεδεμένο με τον απομακρυσμένο κεντρικό υπολογιστή. |
| **bool** [get_DontFragment](./get_dontfragment/)() | Λαμβάνει τιμή που δείχνει αν το socket επιτρέπει τη θραύση των IP datagram. |
| **bool** [get_DualMode](./get_dualmode/)() | Λαμβάνει τιμή που δείχνει αν το socket βρίσκεται σε διπλή λειτουργία. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | Λαμβάνει τιμή που δείχνει αν το socket επιτρέπει πακέτα broadcast. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Λαμβάνει τιμή που δείχνει αν μόνο μία διεργασία μπορεί να δεσμεύσει το socket σε μια θύρα. |
| **bool** [get_IsBound](./get_isbound/)() | Επιστρέφει τιμή που δείχνει αν το socket είναι δεσμευμένο σε συγκεκριμένη τοπική θύρα. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Λαμβάνει τιμή που δείχνει αν το socket θα καθυστερήσει το κλείσιμο προσπαθώντας να στείλει όλα τα εκκρεμή δεδομένα. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | Επιστρέφει το τοπικό endpoint. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | Λαμβάνει τιμή που δείχνει αν το socket λαμβάνει εξερχόμενα multicast πακέτα. |
| **bool** [get_NoDelay](./get_nodelay/)() | Λαμβάνει τιμή που δείχνει αν το socket χρησιμοποιεί τον αλγόριθμο Nagle. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Επιστρέφει τιμή που δείχνει αν το λειτουργικό σύστημα και οι προσαρμογείς δικτύου υποστηρίζουν IPv4. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Επιστρέφει τιμή που δείχνει αν το λειτουργικό σύστημα και οι προσαρμογείς δικτύου υποστηρίζουν IPv6. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | Επιστρέφει τον τύπο πρωτοκόλλου. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Λαμβάνει το μέγεθος του buffer λήψης. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Λαμβάνει την περίοδο μετά την οποία η κλήση 'Receive' θα λήξει. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | Επιστρέφει το απομακρυσμένο endpoint. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Λαμβάνει το μέγεθος του buffer αποστολής. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Λαμβάνει την περίοδο μετά την οποία η κλήση 'Send' θα λήξει. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | Επιστρέφει τον τύπο του socket. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | Επιστρέφει τιμή που δείχνει αν ο τρέχων κεντρικός υπολογιστής υποστηρίζει IPv4. |
| **int16_t** [get_Ttl](./get_ttl/)() | Λαμβάνει την τιμή TTL. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει τη δημιουργία κατακερματισμού για προσαρμοσμένα αντικείμενα. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Επιστρέφει δείκτη στην υλοποίηση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | Επιστρέφει την τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει την τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Επιστρέφει την τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ορίζει λειτουργίες χαμηλού επιπέδου για το socket. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ορίζει λειτουργίες χαμηλού επιπέδου για το socket. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Listen](./listen/)(**int32_t**) | Αλλάζει την κατάσταση του socket σε 'listen'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών σε υποκλάσεις. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | Επιστρέφει την κατάσταση του socket βάσει του καθορισμένου τρόπου polling. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Λαμβάνει δεδομένα από το socket και τα γράφει στους καθορισμένους πίνακες byte. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Λαμβάνει δεδομένα από το socket και τα γράφει στους καθορισμένους πίνακες byte. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Λαμβάνει δεδομένα από το socket και τα γράφει στους καθορισμένους πίνακες byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Λαμβάνει δεδομένα από το καθορισμένο endpoint και τα γράφει στον καθορισμένο πίνακα byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Στέλνει τα καθορισμένα δεδομένα στο socket. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο endpoint. |
| void [set_Blocking](./set_blocking/)(**bool**) | Ορίζει τιμή που δείχνει αν το socket βρίσκεται σε λειτουργία φραγής. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | Ορίζει το χρονικό όριο σύνδεσης. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | Ορίζει τιμή που δείχνει αν το socket επιτρέπει τη θραύση των IP datagram. |
| void [set_DualMode](./set_dualmode/)(**bool**) | Ορίζει τιμή που δείχνει αν το socket βρίσκεται σε διπλή λειτουργία. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | Ορίζει τιμή που δείχνει αν το socket επιτρέπει πακέτα broadcast. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Ορίζει τιμή που δείχνει αν μόνο μία διεργασία μπορεί να δεσμεύσει το socket σε μια θύρα. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Ορίζει τιμή που δείχνει αν το socket θα καθυστερήσει το κλείσιμο προσπαθώντας να στείλει όλα τα εκκρεμή δεδομένα. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | Ορίζει τιμή που δείχνει αν το socket λαμβάνει εξερχόμενα multicast πακέτα. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Ορίζει τιμή που δείχνει αν το socket χρησιμοποιεί τον αλγόριθμο Nagle. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Ορίζει το μέγεθος του buffer λήψης. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Ορίζει την περίοδο μετά την οποία η κλήση 'Receive' θα λήξει. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Ορίζει το μέγεθος του buffer αποστολής. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Ορίζει την περίοδο μετά την οποία η κλήση 'Send' θα λήξει. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | Ορίζει την τιμή TTL. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Ορίζει την καθορισμένη επιλογή socket στην καθορισμένη τιμή. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ορίζει την καθορισμένη επιλογή socket στην καθορισμένη τιμή. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | Ορίζει την καθορισμένη επιλογή socket στην καθορισμένη τιμή. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ορίζει την καθορισμένη επιλογή socket στην καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτές ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτές ή ThisProtector. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | Απενεργοποιεί τις λειτουργίες αποστολής και λήψης του socket. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Δημιουργεί μια νέα παρουσία. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Δημιουργεί μια νέα παρουσία. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τον κατασκευαστή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δεικτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
| virtual  [~Socket](./~socket/)() | Καταστρέφει την τρέχουσα παρουσία. |

## Τύποι με ορισμό

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | Η υλοποίηση του socket. |

## Δείτε επίσης

* Κλάση [IDisposable](../../system/idisposable/)
* Χώρος ονομάτων [System::Net::Sockets](../)
* Βιβλιοθήκη [Aspose.Slides](../../)