---
title: ServicePointManager
second_title: Aspose.Slides για C++ API Αναφορά
description: "Διαχειρίζεται τα στάδια του κύκλου ζωής (δημιουργία, συντήρηση και διαγραφή) των αντικειμένων κλάσης ServicePoint. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο με τη λειτουργία System::MakeObject() function. Ποτέ μην δημιουργήσετε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr pointer και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 430
url: /el/system.net/servicepointmanager/
---
## ServicePointManager κλάση

Διαχειρίζεται τα στάδια του κύκλου ζωής (δημιουργία, συντήρηση και διαγραφή) των [ServicePoint](../servicepoint/) κλάσης. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο με τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργήσετε αντικείμενο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνο εκτέλεσης και/ή αποτυπώσεις. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class ServicePointManager : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με κάποια τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με κάποια τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Ανακτά μια πολιτική πιστοποιητικού. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Ανακτά μια τιμή που υποδεικνύει εάν το πιστοποιητικό πρέπει να ελεγχθεί κατά τη λίστα ανάκλησης αρχής πιστοποιητών. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Ανακτά τον μέγιστο αριθμό ταυτόχρονων συνδέσεων που επιτρέπονται από τα αντικείμενα της κλάσης ServicePoint. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Ανακτά ένα χρονικό όριο σε χιλιοστά του δευτερολέπτου κατά το οποίο μια ανάλυση DNS θεωρείται έγκυρη. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Ανακτά μια τιμή που υποδεικνύει εάν η ανάλυση DNS εναλλάσσεται μεταξύ των εφαρμόσιμων διευθύνσεων IP. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Επιστρέφει την πολιτική κρυπτογράφησης που χρησιμοποιείται από την τρέχουσα παρουσία. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Ανακτά μια τιμή που υποδεικνύει εάν τα αντικείμενα της κλάσης ServicePoint χρησιμοποιούν τη συμπεριφορά 100-Continue. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Ανακτά το μέγιστο χρόνο αδράνειας των αντικειμένων της κλάσης ServicePoint. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Ανακτά τον μέγιστο αριθμό των αντικειμένων της κλάσης ServicePoint που μπορούν να διαχειριστούν από την τρέχουσα παρουσία. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Ανακτά μια τιμή που υποδεικνύει εάν οι υποδοχές εξόδου σύνδεσης χρησιμοποιούν την επιλογή 'SO_REUSE_UNICASTPORT'. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Ανακτά τον τύπο πρωτοκόλλου ασφαλείας που χρησιμοποιείται από τα αντικείμενα της κλάσης ServicePoint που διαχειρίζονται από την τρέχουσα παρουσία. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Ανακτά την κλήση επιστροφής που χρησιμοποιείται για την επικύρωση ενός πιστοποιητικού διακομιστή. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Ανακτά μια τιμή που υποδεικνύει εάν τα αντικείμενα της κλάσης ServicePoint χρησιμοποιούν τον αλγόριθμο Nagle. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ανακτά τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ανακτά τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμετρο αναφοράς κατά την καθορισμένη τιμή. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Ορίζει μια πολιτική πιστοποιητικού. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν το πιστοποιητικό πρέπει να ελεγχθεί κατά τη λίστα ανάκλησης. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Ορίζει τον μέγιστο αριθμό ταυτόχρονων συνδέσεων που επιτρέπεται από τις αντικείμενα της κλάσης ServicePoint. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Ορίζει ένα χρονικό όριο σε χιλιοστά του δευτερολέπτου κατά το οποίο μια ανάλυση DNS θεωρείται έγκυρη. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η ανάλυση DNS εναλλάσσεται μεταξύ των εφαρμόσιμων διευθύνσεων IP. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν τα αντικείμενα της κλάσης ServicePoint χρησιμοποιούν τη συμπεριφορά 100-Continue. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Ορίζει το μέγιστο χρόνο αδράνειας των αντικειμένων της κλάσης ServicePoint. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Ορίζει τον μέγιστο αριθμό αντικειμένων της κλάσης ServicePoint που μπορούν να διαχειριστούν από την τρέχουσα παρουσία. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν οι υποδοχές εξόδου σύνδεσης χρησιμοποιούν την επιλογή 'SO_REUSE_UNICASTPORT'. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Ορίζει τον τύπο πρωτοκόλλου ασφαλείας που χρησιμοποιείται από τα αντικείμενα της κλάσης ServicePoint που διαχειρίζονται από την τρέχουσα παρουσία. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Ορίζει την κλήση επιστροφής που χρησιμοποιείται για την επικύρωση του πιστοποιητικού διακομιστή. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν τα αντικείμενα της κλάσης ServicePoint χρησιμοποιούν τον αλγόριθμο Nagle. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Ορίζει την τιμή που υποδεικνύει εάν η επιλογή 'Keep-Alive' είναι ενεργοποιημένη. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ανακτά την τρέχουσα τιμή του κοινόμετρου αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το κοινόμετρο αναφοράς. Δεν πρέπει να κλήθηκε άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το κοινόμετρο αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Ο προεπιλεγμένος αριθμός μη μόνιμων συνδέσεων. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Ο προεπιλεγμένος αριθμός μόνιμων συνδέσεων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)