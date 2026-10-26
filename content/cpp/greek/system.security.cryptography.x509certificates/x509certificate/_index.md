---
title: X509Certificate
second_title: Aspose.Slides για C++ Αναφορά API
description: "Πιστοποιητικό X.509 v.3. Τα κρυπτογραφημένα πιστοποιητικά δεν υποστηρίζονται. Υποστηρίζεται μόνο η σημαία X509KeyStorageFlags::DefaultKeySet. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτή την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 27
url: /el/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate κλάση


X.509 v.3 πιστοποιητικό. Τα κρυπτογραφημένα πιστοποιητικά δεν υποστηρίζονται. Υποστηρίζεται μόνο η σημαία [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/). Τα αντικείμενα αυτής της κλάσης θα πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτή την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | Δημιουργεί πιστοποιητικό από το καθορισμένο αρχείο PKCS7. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | Δημιουργεί πιστοποιητικό από το καθορισμένο υπογεγραμμένο αρχείο. |
| void [Dispose](./dispose/)() override | Δεν κάνει τίποτα. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει δύο πιστοποιητικά. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | Εξάγει το τρέχον αντικείμενο σε έναν πίνακα byte χρησιμοποιώντας το καθορισμένο μορφότυπο. NOT IMPLEMENTED. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Εξάγει το τρέχον αντικείμενο σε έναν πίνακα byte χρησιμοποιώντας το καθορισμένο μορφότυπο. NOT IMPLEMENTED. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Εξάγει το τρέχον αντικείμενο σε έναν πίνακα byte χρησιμοποιusing the specified format. NOT IMPLEMENTED. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| IntPtr [get_Handle](./get_handle/)() const | Λαμβάνει έναν χειριστή στο περιβάλλον πιστοποιητικού Microsoft Cryptographic API. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | Λαμβάνει το όνομα της αρχής πιστοποιητικών που εξέδωσε το πιστοποιητικό X.509v3. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | Λαμβάνει το διακριτικό όνομα υποκειμένου από το πιστοποιητικό. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | Λαμβάνει το hash του τρέχοντος αντικειμένου ως πίνακα byte. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Λαμβάνει το hash του τρέχοντος αντικειμένου ως πίνακα byte. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | Λαμβάνει το [SHA1](../../system.security.cryptography/sha1/) hash του τρέχοντος αντικειμένου ως δεκαεξαδική συμβολοσειρά. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Λαμβάνει το [SHA1](../../system.security.cryptography/sha1/) hash του τρέχοντος αντικειμένου ως δεκαεξαδική συμβολοσειρά. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | Λαμβάνει την ημερομηνία έναρξης ισχύος του τρέχοντος πιστοποιητικού. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | Λαμβάνει την ημερομηνία λήξης του τρέχοντος πιστοποιητικού. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | Λαμβάνει το όνομα της μορφής του πιστοποιητικού. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Λαμβάνει τον κωδικό hash του πιστοποιητικού. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | Λαμβάνει το όνομα της αρχής πιστοποίησης που εξέδωσε το τρέχον πιστοποιητικό. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | Λαμβάνει τις πληροφορίες κλειδιού για το τρέχον πιστοποιητικό ως συμβολοσειρά. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Λαμβάνει τις πληροφορίες κλειδιού για το τρέχον πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Λαμβάνει τις πληροφορίες κλειδιού για το τρέχον πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | Λαμβάνει το όνομα του κύριου για τον οποίο εκδόθηκε το τρέχον πιστοποιητικό. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | Λαμβάνει το δημόσιο κλειδί από το πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | Λαμβάνει το δημόσιο κλειδί από το πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | Λαμβάνει τα ακατέργαστα δεδομένα από το πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | Λαμβάνει τα ακατέργαστα δεδομένα από το πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | Λαμβάνει τον σειριακό αριθμό από το πιστοποιητικό ως πίνακα byte. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | Λαμβάνει τον σειριακό αριθμό από το πιστοποιητικό ως δεκαεξαδική συμβολοσειρά. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Ανταπόκριση της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Εισάγει πληροφορίες από το καθορισμένο αρχείο πιστοποιητικού. NOT IMPLEMENTED. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Ανταπόκριση του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενα τύπου αναφοράς με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [Reset](./reset/)() | Επαναφέρει την κατάσταση του πιστοποιητικού. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα πρότυπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | Επιστρέφει τις πληροφορίες του πιστοποιητικού σε μορφή κειμένου. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Επιστρέφει τις πληροφορίες του πιστοποιητικού σε μορφή κειμένου. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() |  |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) |  |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) |  |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) |  |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) |  |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) |  |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) |  |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) |  |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) |  |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) |  |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) |  |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) |  |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τύποι ορισμού

| Τύπος ορισμού | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Τύπος δείκτη. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Κλάση [IDisposable](../../system/idisposable/)
* Χώρος ονομάτων [System::Security::Cryptography::X509Certificates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)