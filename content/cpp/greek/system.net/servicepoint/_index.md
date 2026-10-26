---
title: ServicePoint
second_title: Αναφορά API του Aspose.Slides για C++
description: "Παρέχει διαχείριση συνδέσεων HTTP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε εμφάνιση αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 417
url: /el/system.net/servicepoint/
---
## ServicePoint κλάση

Παρέχει διαχείριση συνδέσεων HTTP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ δεν δημιουργείτε εμφάνιση αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class ServicePoint : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | Κλείνει και αφαιρεί συνδέσεις που ανήκουν στην καθορισμένη ομάδα συνδέσεων. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδ·υας σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδ·υας σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Επιστρέφει το URI του διακομιστή στο οποίο συνδέεται η τρέχουσα εμφάνιση. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | Αποκτά τον αντιπροσωπευτικό που χρησιμοποιείται για τη σύνδεση του τοπικού [IPEndPoint](../ipendpoint/) με την τρέχουσα εμφάνιση. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | Επιστρέφει ένα πιστοποιητικό που χρησιμοποιείται από την τρέχουσα εμφάνιση. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | Επιστρέφει το τελευταίο πιστοποιητικό πελάτη. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Αποκτά ένα όριο χρόνου σε χιλιοστά του δευτερολέπτου μετά το οποίο οι ενεργές [ServicePoint](./) θα κλείσουν. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | Αποκτά τον μέγιστο αριθμό συνδέσεων που επιτρέπονται από την τρέχουσα εμφάνιση. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | Επιστρέφει το όνομα της σύνδεσης. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | Επιστρέφει τον αριθμό των ανοιχτών συνδέσεων. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | Αποκτά μια τιμή που υποδηλώνει εάν η συμπεριφορά 100-Continue χρησιμοποιείται. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | Επιστρέφει την ημερομηνία και ώρα της τελευταίας σύνδεσης σε έναν κεντρικό υπολογιστή. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | Αποκτά μια διάρκεια χρόνου σε χιλιοστά του δευτερολέπτου μετά το οποίο μια ανενεργή σύνδεση θα κλείσει. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | Επιστρέφει την έκδοση HTTP. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Αποκτά το μέγεθος του buffer λήψης. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | Επιστρέφει μια τιμή που υποδηλώνει εάν η τρέχουσα εμφάνιση υποστηρίζει τις συνδέσεις σωλήνων. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Αποκτά μια τιμή που υποδηλώνει εάν ο αλγόριθμος Nagle χρησιμοποιείται από τις συνδέσεις που διαχειρίζεται η τρέχουσα εμφάνιση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση αλφαριθμητικού και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση αλφαριθμητικών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει το μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | Ορίζει τον αντιπροσωπευτικό που χρησιμοποιείται για τη σύνδεση του τοπικού [IPEndPoint](../ipendpoint/) με την τρέχουσα εμφάνιση. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | Ορίζει ένα όριο χρόνου σε χιλιοστά του δευτερολέπτου μετά το οποίο οι ενεργές [ServicePoint](./) θα κλείσουν. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | Ορίζει τον μέγιστο αριθμό συνδέσεων που επιτρέπονται από την τρέχουσα εμφάνιση. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Ορίζει μια τιμή που υποδηλώνει εάν η συμπεριφορά 100-Continue χρησιμοποιείται. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | Ορίζει μια διάρκεια χρόνου σε χιλιοστά του δευτερολέπτου μετά το οποίο μια ανενεργή σύνδεση θα κλείσει. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Ορίζει το μέγεθος του buffer λήψης. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Ορίζει μια τιμή που υποδηλώνει εάν ο αλγόριθμος Nagle χρησιμοποιείται από τις συνδέσεις που διαχειρίζεται η τρέχουσα εμφάνιση. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Ορίζει την τιμή που υποδηλώνει εάν η επιλογή 'Keep-Alive' είναι ενεργοποιημένη. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν'οστή όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)