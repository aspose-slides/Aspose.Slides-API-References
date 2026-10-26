---
title: SslStream
second_title: Aspose.Slides για την Αναφορά API C++
description: Μια ροή που χρησιμοποιεί το πρωτόκολλο SSL για την ταυτοποίηση του διακομιστή και προαιρετικά του πελάτη.
type: docs
weight: 14
url: /el/system.net.security/sslstream/
---
## SslStream κλάση

Μία ροή που χρησιμοποιεί το πρωτόκολλο SSL για την ταυτοποίηση του διακομιστή και, προαιρετικά, του πελάτη.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Πιστοποιεί την πλευρά-πελάτη της σύνδεσης. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Πιστοποιεί την πλευρά-πελάτη της σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Ξεκινά μια ασύγχρονη λειτουργία ανάγνωσης. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία ανάγνωσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Ξεκινά μια ασύγχρονη λειτουργία εγγραφής. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία εγγραφής. |
| void [Close](./close/)() override | Κλείνει τη ροή. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Αντιγράφει bytes στη συγκεκριμένη ροή. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Αντιγράφει bytes στη συγκεκριμένη ροή, χρησιμοποιώντας το καθορισμένο **int32_t**. |
| void [Dispose](./dispose/)(**bool**) override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει τη ροή. |
| void [Dispose](../../system.io/stream/dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει τη ροή. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Τερματίζει μια ασύγχρονη λειτουργία εγγραφής. Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία εγγραφής. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Τερματίζει μια ασύγχρονη λειτουργία εγγραφής. Περιμένει έως ότου ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία εγγραφής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| void [Flush](./flush/)() override | Καθαρίζει τις buffers αυτής της ροής και γράφει όλα τα δεδομένα buffer στο υποκείμενο αποθηκευτικό μέσο. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασύγχρονamente καθαρίζει όλα τα buffers για αυτήν τη ροή, επιβάλλει τη γραφή των δεδομένων buffer στη συσκευή-στόχο και παρακολουθεί αιτήματα ακύρωσης. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Ασύγχρονamente καθαρίζει όλα τα buffers για αυτήν τη ροή, επιβάλλει τη γραφή των δεδομένων buffer στη συσκευή-στόχο και παρακολουθεί αιτήματα ακύρωσης. |
| **bool** [get_CanRead](./get_canread/)() const override | Καθορίζει εάν η ροή είναι αναγνώσιμη. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Καθορίζει εάν η ροή υποστηρίζει αναζήτηση. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Επιστρέφει μια τιμή που καθορίζει εάν η τρέχουσα ροή μπορεί να λήξει. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Καθορίζει εάν η ροή είναι εγγράψιμη. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν η λίστα ανάκλησης πιστοποίησης ελέγχεται κατά τη διαδικασία επικύρωσης του πιστοποιητικού. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Επιστρέφει τον αλγόριθμο κρυπτογράφησης. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Επιστρέφει την ισχύ του χρησιμοποιημένου αλγόριθμου κρυπτογράφησης. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Επιστρέφει τον αλγόριθμο hash. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Επιστρέφει την ισχύ του χρησιμοποιημένου αλγόριθμου hash. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Επιστρέφει μια τιμή που υποδεικνύει εάν η ταυτοποίηση ολοκληρώθηκε επιτυχώς. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Επιστρέφει μια τιμή που υποδεικνύει εάν τα δεδομένα που αποστέλλονται μέσω αυτής της ροής είναι κρυπτογραφημένα. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Επιστρέφει μια τιμή που υποδεικνύει εάν ένας διακομιστής και ένας πελάτης είναι ταυτοποιημένοι. |
| **bool** [get_IsServer](./get_isserver/)() const override | Επιστρέφει μια τιμή που υποδεικνύει εάν η τοπική πλευρά της σύνδεσης είναι ο διακομιστής. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Επιστρέφει μια τιμή που υποδεικνύει εάν τα δεδομένα που αποστέλλονται μέσω αυτής της ροής είναι υπογεγραμμένα. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Επιστρέφει την ισχύ του χρησιμοποιημένου αλγόριθμου ανταλλαγής κλειδιών. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Επιστρέφει τη ροή που χρησιμοποιείται από τις τρέχουσες εμφανίσεις της κλάσης για αποστολή και λήψη δεδομένων. |
| **int64_t** [get_Length](./get_length/)() const override | Επιστρέφει το μήκος της ροής σε bytes. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Επιστρέφει το πιστοποιητικό που χρησιμοποιείται για την ταυτοποίηση του τοπικού άκρου. |
| **int64_t** [get_Position](./get_position/)() const override | Επιστρέφει την τρέχουσα θέση της ροής. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Επιστρέφει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο διάστημα η ροή θα προσπαθήσει να διαβάσει πριν λήξει. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Επιστρέφει το πιστοποιητικό που χρησιμοποιείται για την ταυτοποίηση του απομακρυσμένου άκρου. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Επιστρέφει το πρωτόκολλο SSL. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Επιστρέφει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο διάστημα η ροή θα προσπαθήσει να γράψει πριν λήξει. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική με τη μέθοδο C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αποτελεί ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείται απευθείας ή χρησιμοποιείται το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική με τη μέθοδο C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στο καθορισμένο array bytes. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στο καθορισμένο array bytes. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στο καθορισμένο array bytes. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στο καθορισμένο byte span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασύγχρονα διαβάζει μια ακολουθία bytes από την τρέχουσα ροή, προχωρά τη θέση στη ροή κατά τον αριθμό των διαβασμένων bytes και παρακολουθεί αιτήματα ακύρωσης. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Ασύγχρονα διαβάζει μια ακολουθία bytes από την τρέχουσα ροή, προχωρά τη θέση στη ροή κατά τον αριθμό των διαβασμένων bytes και παρακολουθεί αιτήματα ακύρωσης. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Διαβάζει ένα μόνο byte από τη ροή και επιστρέφει μια τιμή 32-bit integer ισοδύναμη με την τιμή του διαβασμένου byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Ορίζει τη θέση της ροής που αντιπροσωπεύει το τρέχον αντικείμενο. |
| void [set_Position](./set_position/)(**int64_t**) override | Ορίζει τη θέση της ροής. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Ορίζει μια τιμή που καθορίζει εάν η τρέχουσα ροή μπορεί να λήξει. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Ορίζει μια τιμή που καθορίζει εάν η τρέχουσα ροή μπορεί να λήξει. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Ορίζει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο διάστημα η ροή θα προσπαθήσει να διαβάσει πριν λήξει. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Ορίζει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο διάστημα η ροή θα προσπαθήσει να διαβάσει πριν λήξει. |
| void [SetLength](./setlength/)(**int64_t**) override | Ορίζει το μήκος της ροής που αντιπροσωπεύει το τρέχον αντικείμενο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα πρότυπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Δημιουργεί μια νέα παρουσία. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Δημιουργεί μια νέα παρουσία. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Δημιουργεί μια νέα παρουσία. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Δημιουργεί μια νέα παρουσία. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Δημιουργεί μια νέα παρουσία. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική με τη μέθοδο C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει το construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιείται το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Γράφει το καθορισμένο array bytes στη ροή. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποδιάστημα bytes από το καθορισμένο array bytes στη ροή. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Γράφει το καθορισμένο array bytes στη ροή. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποδιάστημα bytes από το καθορισμένο array bytes στη ροή. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Γράφει το καθορισμένο υποδιάστημα bytes από το καθορισμένο array bytes στη ροή. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Γράφει το καθορισμένο υποδιάστημα bytes από το καθορισμένο byte span στη ροή. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασύγχρονα γράφει μια ακολουθία bytes στην τρέχουσα ροή, προχωρά τη θέση στη ροή κατά τον αριθμό των γραμμένων bytes και παρακολουθεί αιτήματα ακύρωσης. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Ασύγχρονα γράφει μια ακολουθία bytes στην τρέχουσα ροή, προχωρά τη θέση στη ροή κατά τον αριθμό των γραμμένων bytes και παρακολουθεί αιτήματα ακύρωσης. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Γράφει την καθορισμένη unsigned 8-bit integer τιμή στη ροή. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Μια ροή χωρίς υποκείμενη αποθήκευση. |

## Ορισμοί τύπου

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Τύπος του AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Τύπος δείκτη προς την υλοποίηση. |

## Δείτε επίσης

* Κλάση [AuthenticatedStream](../authenticatedstream/)
* Χώρος ονομάτων [System::Net::Security](../)
* Βιβλιοθήκη [Aspose.Slides](../../)