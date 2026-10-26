---
title: SoapDocumentMethodAttribute
second_title: "Αναφορά API Aspose.Slides για C++"
description: "Καθορίζει ότι όλα τα μηνύματα SOAP που περνούν ή επιστρέφονται από τη μέθοδο χρησιμοποιούν τη μορφοποίηση Document. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτήν τη κλάση με δείκτη System::SmartPtr και χρησιμοποιείτε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως παράμετρο."
type: docs
weight: 53
url: /el/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute κλάση

Καθορίζει ότι όλα τα μηνύματα SOAP που περνούν ή επιστρέφονται από τη μέθοδο χρησιμοποιούν τη μορφοποίηση Document. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούν μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ δεν πρέπει να δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να περιβάλλετε αυτή τη κλάση με δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως παράμετρο.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση σημειακών αριθμών σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση σημειακών αριθμών σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [String](../../system/string/) [get_Action](./get_action/)() | Λαμβάνει μια τιμή του χαρακτηριστικού 'SOAPAction'. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | Λαμβάνει την σύνδεση για την οποία μια μέθοδος υπηρεσίας ιστού XML υλοποιεί μια ενέργεια. |
| **bool** [get_OneWay](./get_oneway/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν ένας πελάτης δεν περιμένει τον διακομιστή να ολοκληρώσει την επεξεργασία μιας μεθόδου. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν οι παράμετροι είναι ενσωματωμένες μέσα σε ένα μόνο στοιχείο XML κάτω από το στοιχείο 'Body'. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | Λαμβάνει το όνομα του στοιχείου XML που σχετίζεται με το αίτημα SOAP, το οποίο ορίζεται σε περιγραφή υπηρεσίας ως ενέργεια. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | Λαμβάνει το χώρο ονομάτων που σχετίζεται με το αίτημα SOAP. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | Λαμβάνει το όνομα του στοιχείου XML που σχετίζεται με την απόκριση SOAP. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | Λαμβάνει το χώρο ονομάτων που σχετίζεται με την απόκριση SOAP. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | Λαμβάνει μια τιμή που καθορίζει τη μέθοδο κωδικοποίησης του μηνύματος. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Επιστρέφει ένα προσαρμοσμένο χαρακτηριστικό συγκεκριμένου τύπου που εφαρμόζεται σε συγκεκριμένο τύπο. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Επιστρέφει όλα τα προσαρμοσμένα χαρακτηριστικά που εφαρμόζονται σε συγκεκριμένο τύπο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_Action](./set_action/)([String](../../system/string/)) | Ορίζει μια τιμή του χαρακτηριστικού 'SOAPAction'. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | Ορίζει τη σύνδεση για την οποία μια μέθοδος υπηρεσίας ιστού XML υλοποιεί μια ενέργεια. |
| void [set_OneWay](./set_oneway/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν ο πελάτης δεν περιμένει τον διακομιστή να ολοκληρώσει την επεξεργασία μιας μεθόδου. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | Ορίζει μια τιμή που υποδεικνύει εάν οι παράμετροι είναι ενσωματωμένες σε ένα μόνο στοιχείο XML κάτω από το στοιχείο 'Body'. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | Ορίζει το όνομα του στοιχείου XML που σχετίζεται με το αίτημα SOAP, το οποίο ορίζεται σε περιγραφή υπηρεσίας ως ενέργεια. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | Ορίζει το χώρο ονομάτων που σχετίζεται με το αίτημα SOAP. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | Ορίζει το όνομα του στοιχείου XML που σχετίζεται με την απόκριση SOAP. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | Ορίζει το χώρο ονομάτων που σχετίζεται με την απόκριση SOAP. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Ορίζει μια τιμή που καθορίζει τη μέθοδο κωδικοποίησης του μηνύματος. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα πρότυπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Δημιουργεί ένα νέο στιγμιότυπο. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | Δημιουργεί ένα νέο στιγμιότυπο. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Attribute](../../system/attribute/)
* Χώρος ονομάτων [System::Web::Services::Protocols](../)
* Βιβλιοθήκη [Aspose.Slides](../../)