---
title: X509Certificate2
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αναπαριστά πιστοποιητικό X509. Τα αντικείμενα αυτής της κλάσης πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 40
url: /el/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 κλάση

Αντιπροσωπεύει το πιστοποιητικό X509. Τα αντικείμενα αυτής της κλάσης πρέπει να κατασκευάζονται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | Δημιουργεί πιστοποιητικό από το καθορισμένο αρχείο PKCS7. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | Δημιουργεί πιστοποιητικό από το καθορισμένο υπογεγραμμένο αρχείο. |
| void [Dispose](../x509certificate/dispose/)() override | Δεν κάνει τίποτα. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει δύο πιστοποιητικά. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει την σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει την σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | Εξάγει το τρέχον αντικείμενο σε πίνακα byte χρησιμοποιώντας το καθορισμένο μορφότυπο. ΔΕΝ ΥΑΛΟΠΟΙΗΘΗΚΕ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Εξάγει το τρέχον αντικείμενο σε πίνακα byte χρησιμοποιώντας το καθορισμένο μορφότυπο. ΔΕΝ ΥΑΛΟΠΟΙΗΘΗΚΕ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Εξάγει το τρέχον αντικείμενο σε πίνακα byte χρησιμοποιώντας το καθορισμένο μορφότυπο. ΔΕΝ ΥΑΛΟΠΟΙΗΘΗΚΕ. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_Archived](./get_archived/)() const | Επιστρέφει μια τιμή που υποδεικνύει ότι το πιστοποιητικό είναι αρχειοθετημένο. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | Επιστρέφει τη συλλογή αντικειμένων επέκτασης που σχετίζονται με το πιστοποιητικό. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | Επιστρέφει το φιλικό όνομα του πιστοποιητικού. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | Επιστρέφει έναν χειριστή στο πλαίσιο πιστοποιητικού του Microsoft Cryptographic API. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | Ελέγχει εάν το πιστοποιητικό διαθέτει ιδιωτικό κλειδί. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | Επιστρέφει το όνομα της αρχής έκδοσης του πιστοποιητικού X.509v3. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | Επιστρέφει το όνομα του μέρους που έκδεσεν πιστοποιητικό. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | Επιστρέφει την τοπική ημερομηνία και ώρα μετά την οποία το πιστοποιητικό δεν είναι πλέον έγκυρο. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | Επιστρέφει την τοπική ημερομηνία και ώρα που το πιστοποιητικό γίνεται έγκυρο. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | Επιστρέφει το ιδιωτικό κλειδί που συσχετίζεται με το πιστοποιητικό. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | Επιστρέφει ένα αντικείμενο [PublicKey](../publickey/) πιστοποιητικού. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | Επιστρέφει τα ακατέργαστα δεδομένα του πιστοποιητικού. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | Επιστρέφει τον σειριακό αριθμό ενός πιστοποιητικού. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Επιστρέφει τον αλγόριθμο που χρησιμοποιείται για τη δημιουργία της υπογραφής ενός πιστοποιητικού. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | Επιστρέφει το διακριτικό όνομα του υποκειμένου από το πιστοποιητικό. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | Επιστρέφει το όνομα του υποκειμένου από ένα πιστοποιητικό. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | Επιστρέφει το αποτύπωμα του πιστοποιητικού. |
| **int32_t** [get_Version](./get_version/)() const | Επιστρέφει την έκδοση μορφής του πιστοποιητικού. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Επιστρέφει τον τύπο του πιστοποιητικού που περιέχεται στον καθορισμένο πίνακα byte. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | Επιστρέφει τον τύπο του πιστοποιητικού που περιέχεται στο καθορισμένο αρχείο. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | Επιστρέφει το hash του τρέχοντος αντικειμένου ως πίνακα byte. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Επιστρέφει το hash του τρέχοντος αντικειμένου ως πίνακα byte. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | Επιστρέφει το hash [SHA1](../../system.security.cryptography/sha1/) του τρέχοντος αντικειμένου ως δεκαεξαδική συμβολοσειρά. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Επιστρέφει το hash [SHA1](../../system.security.cryptography/sha1/) του τρέχοντος αντικειμένου ως δεκαεξαδική συμβολοσειρά. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Επιστρέφει την δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | Επιστρέφει το ιδιωτικό κλειδί [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | Επιστρέφει το δημόσιο κλειδί [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Επιστρέφει το ιδιωτικό κλειδί [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | Επιστρέφει το δημόσιο κλειδί [RSA](../../system.security.cryptography/rsa/). |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | Επιστρέφει την ημερομηνία ισχύος του τρέχοντος πιστοποιητικού. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | Επιστρέφει την ημερομηνία λήξης του τρέχοντος πιστοποιητικού. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | Επιστρέφει το όνομα του μορφότυπου του πιστοποιητικού. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | Επιστρέφει τον κωδικό hash του πιστοποιητικού. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | Επιστρέφει το όνομα της αρχής πιστοποίησης που εξέδωσε το τρέχον πιστοποιητικό. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | Επιστρέφει τις πληροφορίες κλειδιού για το τρέχον πιστοποιητικό ως συμβολοσειρά. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | Επιστρέφει τις πληροφορίες κλειδιού για το τρέχον πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | Επιστρέφει τις πληροφορίες κλειδιού για το τρέχον πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | Επιστρέφει το όνομα του κύριου για τον οποίο εκδόθηκε το τρέχον πιστοποιητικό. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | Επιστρέφει το όνομα υποκειμένου ή εκδότη από το πιστοποιητικό. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | Επιστρέφει το δημόσιο κλειδί από το πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | Επιστρέφει το δημόσιο κλειδί από το πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | Επιστρέφει τα ακατέργαστα δεδομένα από το πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | Επιστρέφει τα ακατέργαστα δεδομένα από το πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | Επιστρέφει το ιδιωτικό κλειδί [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | Επιστρέφει το δημόσιο κλειδί [RSA](../../system.security.cryptography/rsa/). |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | Επιστρέφει τον σειριακό αριθμό από το πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | Επιστρέφει τον σειριακό αριθμό από το πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Επιστρέφει τον πραγματικό τύπο του αντικειμένου. Αντίστροφο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Εισάγει πληροφορίες από τα καθορισμένα δεδομένα πιστοποιητικού. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Εισάγει πληροφορίες από τα καθορισμένα δεδομένα πιστοποιητικού. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | Εισάγει πληροφορίες από τα καθορισμένα δεδομένα πιστοποιητικού. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεσoperator ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά ενός αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [Reset](./reset/)() override | Επαναφέρει την κατάσταση του πιστοποιητικού. |
| void [set_Archived](./set_archived/)(**bool**) const | Ορίζει μια τιμή που υποδεικνύει ότι το πιστοποιητικό είναι αρχειοθετημένο. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | Ορίζει το φιλικό όνομα του πιστοποιητικού. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | Ορίζει ή καθαρίζει το ιδιωτικό κλειδί που συσχετίζεται με το πιστοποιητικό. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Επιστρέφει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | Επιστρέφει τις πληροφορίες του πιστοποιητικού σε μορφή κειμένου. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Επιστρέφει τις πληροφορίες του πιστοποιητικού σε μορφή κειμένου. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| **bool** [Verify](./verify/)() const | Επαληθεύει την αλυσίδα πιστοποιητικών. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|  [X509Certificate](../x509certificate/x509certificate/)() | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)() | Δημιουργεί κενό [X509Certificate2](./). |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Κατασκευαστής. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [X509Certificate](../x509certificate/)
* Χώρος ονομάτων [System::Security::Cryptography::X509Certificates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)