---
title: Cookie
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αντιπροσωπεύει ένα cookie HTTP. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 1
url: /el/system.net/cookie/
---
## Κλάση Cookie

Αναπαριστά ένα HTTP cookie. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα.

```cpp
class Cookie : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου. |
| [Cookie](./cookie/)() | Δημιουργεί ένα νέο αντικείμενο. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Δημιουργεί ένα νέο αντικείμενο. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Δημιουργεί ένα νέο αντικείμενο. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Δημιουργεί ένα νέο αντικείμενο. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Παίρνει την τιμή του χαρακτηριστικού 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Παίρνει την τιμή του χαρακτηριστικού 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Παίρνει την τιμή του χαρακτηριστικού 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Παίρνει την τιμή του χαρακτηριστικού 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Παίρνει μια τιμή που δείχνει αν ο τομέας είναι έμμεσος. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Επιστρέφει το κλειδί του τομέα. |
| **bool** [get_Expired](./get_expired/)() | Παίρνει μια τιμή που δείχνει αν το cookie έληξε. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Παίρνει την τιμή του χαρακτηριστικού 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Παίρνει την τιμή του χαρακτηριστικού 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Παίρνει το όνομα του cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Παίρνει την τιμή του χαρακτηριστικού 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Επιστρέφει μια τιμή που δείχνει αν η προδιαγραφή του cookie είναι 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Παίρνει την τιμή του χαρακτηριστικού 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Επιστρέφει τη συλλογή των τιμών του χαρακτηριστικού 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Παίρνει την τιμή του χαρακτηριστικού 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Επιστρέφει την ώρα δημιουργίας του cookie. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Παίρνει την τιμή του cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Παίρνει την προδιαγραφή του cookie. |
| **int32_t** [get_Version](./get_version/)() const | Παίρνει την τιμή του χαρακτηριστικού '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Αυτή η μέθοδος καλείται από άλλες μεθόδους για να θέσει ένα όνομα μεθόδου. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων των υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων των υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Ορίζει την τιμή του χαρακτηριστικού 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Ορίζει την τιμή του χαρακτηριστικού 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Ορίζει την τιμή του χαρακτηριστικού 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Ορίζει την τιμή του χαρακτηριστικού 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Ορίζει μια τιμή που δείχνει αν ο τομέας είναι έμμεσος. |
| void [set_Expired](./set_expired/)(**bool**) | Ορίζει μια τιμή που δείχνει αν το cookie έληξε. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Ορίζει την τιμή του χαρακτηριστικού 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Ορίζει την τιμή του χαρακτηριστικού 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Ορίζει το όνομα του cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Ορίζει την τιμή του χαρακτηριστικού 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Ορίζει την τιμή του χαρακτηριστικού 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Ορίζει την τιμή του χαρακτηριστικού 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Ορίζει την τιμή του cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Ορίζει την προδιαγραφή του cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Ορίζει την τιμή του χαρακτηριστικού '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th ορίσμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή των δεικτών στα containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Σειριοποιεί την τρέχουσα παρουσία σε αναπαράσταση συμβολοσειράς. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Ελέγχει και ορίζει τις προεπιλεγμένες τιμές των χαρακτηριστικών. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Το όνομα του χαρακτηριστικού 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Το όνομα του χαρακτηριστικού 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Το όνομα του χαρακτηριστικού 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Το όνομα του χαρακτηριστικού 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Ο διαχωριστής που χρησιμοποιείται για το διαχωρισμό του ονόματος και της τιμής ενός χαρακτηριστικού. |
| static [ExpiresAttributeName](./expiresattributename/) | Το όνομα του χαρακτηριστικού 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Το όνομα του χαρακτηριστικού 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Το όνομα του χαρακτηριστικού 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Η μέγιστη υποστηριζόμενη έκδοση. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Η αναπαράσταση συμβολοσειράς της μέγιστης υποστηριζόμενης έκδοσης. |
| static [PathAttributeName](./pathattributename/) | Το όνομα του χαρακτηριστικού 'Path'. |
| static [PortAttributeName](./portattributename/) | Το όνομα του χαρακτηριστικού 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Ο πίνακας που περιέχει διαχωριστικά για τις τιμές του χαρακτηριστικού 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Το σύμβολο που χρησιμοποιείται για την περιτύλιξη των τμημάτων του χαρακτηριστικού. |
| static [ReservedToName](./reservedtoname/) | Μια τιμή που είναι δεσμευμένη για το όνομα του cookie. |
| static [ReservedToValue](./reservedtovalue/) | Μια τιμή που είναι δεσμευμένη για την τιμή του cookie. |
| static [SecureAttributeName](./secureattributename/) | Το όνομα του χαρακτηριστικού 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Ο διαχωριστής χαρακτηριστικών. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Το πρόθεμα των ονομάτων των ειδικών χαρακτηριστικών. |
| static [VersionAttributeName](./versionattributename/) | Το όνομα του χαρακτηριστικού '[Version](../../system/version/)'. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Ονομαχώρος [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)