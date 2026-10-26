---
title: IConvertible
second_title: Αναφορά API Aspose.Slides για C++
description: "Ορίζει μεθόδους που μετατρέπουν την τιμή του υλοποιούμενου τύπου αναφοράς ή τιμής σε έναν τύπο χρόνου εκτέλεσης κοινής γλώσσας που έχει ισοδύναμη τιμή. Τα αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 937
url: /el/system/iconvertible/
---
## IConvertible κλάση

Ορίζει μεθόδους που μετατρέπουν την τιμή του υλοποιημένου αναφοράς ή τύπου τιμής σε έναν τύπο χρόνου εκτέλεσης κοινής γλώσσας που έχει ισοδύναμη τιμή. Τα αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργείτε ένα αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class IConvertible : public virtual System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Μιμείται τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Μιμείται τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Επιτρέπει το hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../object/gettype/). |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | Επιστρέφει τον κωδικό τύπου για αυτήν την παρουσία. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κληθεί απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση του string και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση των strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδυναμική λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμη τιμή [Boolean](../boolean/) χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 8-bit uint32_teger χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο χαρακτήρα Unicode χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο [System::DateTime](../datetime/) χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο αριθμό [System::Decimal](../decimal/) χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο αριθμό double-precision floating-point χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 16-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 32-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 64-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 8-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο single-precision floating-point αριθμό χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο [System::String](../string/) χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual [String](../string/) [ToString](./tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε [System::Object](../object/) του καθορισμένου System::Type που έχει ισοδύναμη τιμή, χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 16-bit uint32_teger χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 32-bit uint32_teger χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Μετατρέπει την τιμή αυτής της παρουσίας σε ισοδύναμο 64-bit uint32_teger χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικής κουλτούρας. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κληθεί απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτείας [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../object/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)