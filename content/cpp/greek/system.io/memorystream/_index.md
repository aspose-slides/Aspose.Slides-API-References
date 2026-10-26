---
title: MemoryStream
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει μια ροή που διαβάζει από και γράφει στη μνήμη. Τα αντικείμενα αυτής της κλάσης πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 326
url: /el/system.io/memorystream/
---
## MemoryStream κλάση


Αντιπροσωπεύει μια ροή που διαβάζει από και γράφει στη μνήμη. Τα αντικείμενα αυτής της κλάσης πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα.

```cpp
class MemoryStream : public System::IO::Stream
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία ανάγνωσης. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία εγγραφής. |
| void [Close](./close/)() override | Κλείνει τη ροή. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Αντιγράφει bytes στο καθορισμένο ρεύμα. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Αντιγράφει bytes στο καθορισμένο ρεύμα, χρησιμοποιώντας το καθορισμένο μέγεθος buffer. |
| void [Dispose](../stream/dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει τη ροή. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Τελειώνει μια ασύγχρονη λειτουργία εγγραφής. Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία εγγραφής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| void [Flush](./flush/)() override | Δεν κάνει τίποτα. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασυγχρόνως εκκαθαρίζει όλα τα buffers για αυτή τη ροή, προκαλεί την εγγραφή τυχόν buffered δεδομένων στη βασική συσκευή, και παρακολουθεί αιτήματα ακύρωσης. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Ασυγχρόνως εκκαθαρίζει όλα τα buffers για αυτή τη ροή, προκαλεί την εγγραφή τυχόν buffered δεδομένων στη βασική συσκευή, και παρακολουθεί αιτήματα ακύρωσης. |
| **bool** [get_CanRead](./get_canread/)() const override | Καθορίζει αν η ροή είναι αναγνώσιμη. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Καθορίζει αν η ροή υποστηρίζει αναζήτηση. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Παίρνει μια τιμή που καθορίζει αν η τρέχουσα ροή μπορεί να λήξει (time out). |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Καθορίζει αν η ροή είναι εγγράψιμη. |
| int [get_Capacity](./get_capacity/)() | Επιστρέφει την τρέχουσα χωρητικότητα του υποκείμενου buffer μνήμης. |
| **int64_t** [get_Length](./get_length/)() const override | Επιστρέφει το μήκος της ροής σε bytes. |
| **int64_t** [get_Position](./get_position/)() const override | Επιστρέφει τη τρέχουσα θέση της ροής. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Παίρνει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο χρόνο θα προσπαθήσει η ροή να διαβάσει πριν λήξει. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Παίρνει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο χρόνο θα προσπαθήσει η ροή να γράψει πριν λήξει. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | Επιστρέφει δείκτη στο υποκείμενο buffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την εντολή κλειδώματος C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [MemoryStream](./memorystream/)() | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [MemoryStream](./) με αρχική χωρητικότητα ίση με 0. |
|  [MemoryStream](./memorystream/)(int) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [MemoryStream](./) που αντιπροσωπεύει μια ροή βασισμένη σε buffer μνήμης του καθορισμένου μεγέθους. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [MemoryStream](./) που αντιπροσωπεύει μια ροή μνήμης που είναι συνδεδεμένη με το καθορισμένο buffer μνήμης. Ένα παράμετρος καθορίζει αν η ροή είναι εγγράψιμη. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [MemoryStream](./) που αντιπροσωπεύει μια ροή μνήμης που είναι συνδεδεμένη σε ένα τμήμα του καθορισμένου buffer μνήμης, αρχίζοντας από το καθορισμένο δείκτη και περιλαμβάνοντας τον καθορισμένο αριθμό στοιχείων. Οι παράμετροι καθορίζουν αν η ροή είναι εγγράψιμη και αν μπορεί να κληθεί η μέθοδος GetBytes(). |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων σε υποκλάσεις. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα byte. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα byte. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στο καθορισμένο byte span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασυγχρόνως διαβάζει μια ακολουθία bytes από την τρέχουσα ροή, προχωρά τη θέση εντός της ροής κατά τον αριθμό των διαβασμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Ασυγχρόνως διαβάζει μια ακολουθία bytes από την τρέχουσα ροή, προχωρά τη θέση εντός της ροής κατά τον αριθμό των διαβασμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| int [ReadByte](./readbyte/)() override | Διαβάζει ένα ενιαίο byte από τη ροή και επιστρέφει μια τιμή 32-bit integer ισοδύναμη με την τιμή του διαβασμένου byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Ορίζει τη θέση της ροής που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [set_Capacity](./set_capacity/)(int) | Ορίζει τη χωρητικότητα του υποκείμενου buffer μνήμης. |
| void [set_Position](./set_position/)(**int64_t**) override | Ορίζει τη θέση της ροής. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Ορίζει μια τιμή που καθορίζει αν η τρέχουσα ροή μπορεί να λήξει. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Ορίζει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο χρόνο θα προσπαθήσει η ροή να διαβάσει πριν λήξει. |
| void [SetLength](./setlength/)(**int64_t**) override | Ορίζει το μήκος της ροής που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | Επιστρέφει ένα αντίγραφο του υποκείμενου buffer μνήμης ως πίνακα bytes. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | Επιστρέφει τον πίνακα των unsigned bytes από τα οποία δημιουργήθηκε αυτή η ροή. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της εντολής C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποσύνολο bytes από τον καθορισμένο πίνακα byte στη ροή. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποσύνολο bytes από τον καθορισμένο πίνακα byte στη ροή. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Γράφει το καθορισμένο υποσύνολο bytes από τον καθορισμένο πίνακα byte στη ροή. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Γράφει το καθορισμένο υποσύνολο bytes από το καθορισμένο byte span στη ροή. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασυγχρόνως γράφει μια ακολουθία bytes στην τρέχουσα ροή, προχωρά την τρέχουσα θέση εντός αυτής της ροής κατά τον αριθμό των γραμμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Ασυγχρόνως γράφει μια ακολουθία bytes στην τρέχουσα ροή, προχωρά την τρέχουσα θέση εντός αυτής της ροής κατά τον αριθμό των γραμμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Γράφει την καθορισμένη unsigned 8-bit integer τιμή στη ροή. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | Γράφει το περιεχόμενο του υποκείμενου buffer στη καθορισμένη ροή. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [Null](../stream/null/) | Μια ροή χωρίς υποκείμενη αποθήκευση. |
## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για έναν shared pointer στον εαυτό. |
## Δείτε επίσης

* Κλάση [Stream](../stream/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)