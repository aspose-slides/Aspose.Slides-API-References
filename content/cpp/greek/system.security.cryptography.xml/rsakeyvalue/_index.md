---
title: RSAKeyValue
second_title: "Αναφορά API του Aspose.Slides για C++"
description: "Αντιπροσωπεύει το στοιχείο 'RSAKeyValue' της υπογραφής XML. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφαλμάτων αστοχίας. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως παράμετρο."
type: docs
weight: 92
url: /el/system.security.cryptography.xml/rsakeyvalue/
---
## RSAKeyValue κλάση

Αναπαριστά το στοιχείο '[RSAKeyValue](./)' της υπογραφής XML. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε μια εμφάνιση αυτού του τύπου στη στοίβα ή χρησιμοποιώντας το τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα αστοχίας. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε λειτουργίες ως παράμετρο.

```cpp
class RSAKeyValue : public System::Security::Cryptography::Xml::KeyInfoClause
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaNs θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaNs θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [get_Key](./get_key/)() |  |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() |  |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικευμένη έκδοση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικευμένη έκδοση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
|  [RSAKeyValue](./rsakeyvalue/)() |  |
|  [RSAKeyValue](./rsakeyvalue/)([SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\>) |  |
| void [set_Key](./set_key/)([SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\>) |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποεναλλαγή της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεία· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [KeyInfoClause](../keyinfoclause/)
* Χώρος ονομάτων [System::Security::Cryptography::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)