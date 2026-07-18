---
title: BasicSTDOStreamWrapper
second_title: Aspose.Slides για το C++ API Αναφορά
description: "Αντιπροσωπεύει ένα περιτύλιγμα τύπου System.IO.Stream για το std::basic_ostream και τα παράγωγά του. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 27
url: /el/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper κλάση

Αντιπροσωπεύει ένα περιτύλιγμα τύπου [System.IO.Stream](../stream/) για το std::basic_ostream και τα παράγωγά του. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Δημιουργεί μια νέα παρουσία του [BasicSTDOStreamWrapper](./). |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | Κατασκευαστής αντιγραφής. Διαγραμμένος. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία ανάγνωσης. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ξεκινά μια ασύγχρονη λειτουργία εγγραφής. |
| virtual void [Close](../stream/close/)() | Κλείνει το ρεύμα. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Αντιγράφει bytes στο καθορισμένο ρεύμα. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Αντιγράφει bytes στο καθορισμένο ρεύμα, χρησιμοποιώντας το καθορισμένο μέγεθος buffer. |
| void [Dispose](../stream/dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί το τρέχον αντικείμενο και κλείνει το ρεύμα. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Τελειώνει μια ασύγχρονη λειτουργία εγγραφής. Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία εγγραφής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| void [Flush](./flush/)() override | Καθαρίζει τα buffers του ρεύματος και γράφει όλα τα δεδομένα buffer στο υποκείμενο αποθηκευτικό μέσο. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασύγχρονα καθαρίζει όλα τα buffers για αυτό το ρεύμα, προκαλεί την εγγραφή των δεδομένων buffer στη συσκευή υποδοχής, και παρακολουθεί αιτήματα ακύρωσης. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Ασύγχρονα καθαρίζει όλα τα buffers για αυτό το ρεύμα, προκαλεί την εγγραφή των δεδομένων buffer στη συσκευή υποδοχής, και παρακολουθεί αιτήματα ακύρωσης. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | Καθορίζει αν το ρεύμα υποστηρίζει ανάγνωση. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Καθορίζει αν το ρεύμα υποστηρίζει αναζήτηση. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Λαμβάνει μια τιμή που καθορίζει αν το τρέχον ρεύμα μπορεί να λήξει. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Επιστρέφει το μήκος του ρεύματος. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Επιστρέφει την τρέχουσα θέση του ρεύματος. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Λαμβάνει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο χρόνο το ρεύμα θα προσπαθήσει να διαβάσει πριν λήξει. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Λαμβάνει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο χρόνο το ρεύμα θα προσπαθήσει να γράψει πριν λήξει. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | Τελεσάτορ ανάθεσης αντιγραφής. Διαγραμμένο. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Τελεσάτορ ανάθεσης αντιγραφής. Διαγραμμένο. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεσάτορ ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Αν η λειτουργία περιτυλίγματος είναι δυαδική, διαβάζει τον καθορισμένο αριθμό bytes από το ρεύμα, διαφορετικά διαβάζει τον καθορισμένο αριθμό χαρακτήρων και τους μετατρέπει σε τύπο **uint8_t**. Γράφει το αποτέλεσμα της ανάγνωσης στον καθορισμένο πίνακα bytes. Δεν υποστηρίζεται! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Διαβάζει τον καθορισμένο αριθμό bytes από το ρεύμα και τα γράφει στον καθορισμένο πίνακα bytes. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Διαβάζει τον καθορισμένο αριθμό bytes από το ρεύμα και τα γράφει στον καθορισμένο πίνακα bytes. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Διαβάζει τον καθορισμένο αριθμό bytes από το ρεύμα και τα γράφει στον καθορισμένο πίνακα bytes. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασύγχρονα διαβάζει μια ακολουθία bytes από το τρέχον ρεύμα, προχωρά τη θέση εντός του ρεύματος κατά τον αριθμό των διαβασμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Ασύγχρονα διαβάζει μια ακολουθία bytes από το τρέχον ρεύμα, προχωρά τη θέση εντός του ρεύματος κατά τον αριθμό των διαβασμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| int [ReadByte](./readbyte/)() override | Αν η λειτουργία περιτυλίγματος είναι δυαδική, διαβάζει ένα μόνο byte από την τελευταία αποθήκευση αποκωδικοποιημένου χαρακτήρα, διαφορετικά διαβάζει έναν μόνο χαρακτήρα από το ρεύμα και τον μετατρέπει σε τύπο **uint8_t**. Δεν υποστηρίζεται! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | Πληροφορίες RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Θέτει τη θέση του ρεύματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Θέτει τη θέση του ρεύματος. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Θέτει μια τιμή που καθορίζει αν το τρέχον ρεύμα μπορεί να λήξει. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Θέτει μια τιμή, σε χιλιοστά του δευτερολέπτου, που καθορίζει πόσο χρόνο το ρεύμα θα προσπαθήσει να διαβάσει πριν λήξει. |
| void [SetLength](./setlength/)(**int64_t**) override | Θέτει το μήκος του ρεύματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Θέτει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Κατασκευαστής αντιγραφής. Διαγραμμένος. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί για αυτό, χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Αν η λειτουργία περιτυλίγματος είναι δυαδική, γράφει στο ρεύμα το καθορισμένο υποσύνολο bytes από τον καθορισμένο πίνακα bytes, διαφορετικά μετατρέπει το καθορισμένο υποσύνολο bytes από τον πίνακα σε τύπο char_type και έπειτα γράφει το αποτέλεσμα στο ρεύμα. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Γράφει το καθορισμένο υποσύνολο bytes από τον καθορισμένο πίνακα bytes στο ρεύμα. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Γράφει το καθορισμένο υποσύνολο bytes από τον πίνακα bytes στο ρεύμα. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Γράφει το καθορισμένο υποσύνολο bytes από το καθορισμένο byte span στο ρεύμα. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Ασύγχρονα γράφει μια ακολουθία bytes στο τρέχον ρεύμα, προχωρά τη τρέχουσα θέση εντός του ρεύματος κατά τον αριθμό των γραμμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Ασύγχρονα γράφει μια ακολουθία bytes στο τρέχον ρεύμα, προχωρά τη τρέχουσα θέση εντός του ρεύματος κατά τον αριθμό των γραμμένων bytes, και παρακολουθεί αιτήματα ακύρωσης. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Αν η λειτουργία περιτυλίγματος είναι δυαδική, γράφει στο ρεύμα την καθορισμένη μη-α signed τιμή 8-bit, διαφορετικά τη μετατρέπει σε τύπο char_type και έπειτα γράφει το αποτέλεσμα στο ρεύμα. |
| virtual  [~Object](../../system/object/~object/)() | Καταστραφεί αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [Null](../stream/null/) | Ένα ρεύμα χωρίς υποκείμενο αποθηκευτικό μέσο. |

## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Δείτε επίσης

* Κλάση [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)