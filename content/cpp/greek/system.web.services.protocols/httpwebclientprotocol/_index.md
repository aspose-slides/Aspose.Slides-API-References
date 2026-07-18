---
title: HttpWebClientProtocol
second_title: Αναφορά API του Aspose.Slides για C++
description: "Αυτή η κλάση βάσης χρησιμοποιείται σε όλους τους διαμεσολαβητές πελατών υπηρεσίας Web XML που χρησιμοποιούν HTTP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο με τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 14
url: /el/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol κλάση

Αυτή η κλάση βάσης χρησιμοποιείται σε όλα τα προσιμά κλήσης πελάτη υπηρεσίας XML [Web](../../system.web/) που χρησιμοποιούν HTTP. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο με τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Ακυρώνει το αίτημα. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Προσθέτει cookies από το συγκεκριμένο αίτημα στον εσωτερικό χώρο αποθήκευσης cookies. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν ο πελάτης ακολουθεί τις ανακατευθύνσεις του διακομιστή. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Επιστρέφει τη συλλογή των πιστοποιητικών του πελάτη. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Λαμβάνει το όνομα της ομάδας σύνδεσης. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Λαμβάνει έναν χώρο αποθήκευσης που χρησιμοποιείται για την αποθήκευση cookies. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Λαμβάνει τις πληροφορίες πιστοποίησης. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | Λαμβάνει μια τιμή που υποδεικνύει αν η αποσυμπίεση είναι ενεργοποιημένη. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Λαμβάνει μια τιμή που υποδεικνύει αν η προ-πιστοποίηση είναι ενεργοποιημένη. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | Λαμβάνει πληροφορίες διαμεσολαβητή. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Λαμβάνει την κωδικοποίηση που χρησιμοποιείται για τις αιτήσεις του πελάτη. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Λαμβάνει το χρονικό διάστημα αναμονής πριν λήξει το αίτημα. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν η κοινή χρήση σύνδεσης είναι ενεργοποιημένη όταν ο πελάτης χρησιμοποιεί πιστοποίηση NTLM. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Λαμβάνει το URI της υπηρεσίας XML [Web](../../system.web/). |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Λαμβάνει τη διεύθυνση URL της υπηρεσίας XML [Web](../../system.web/). |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Λαμβάνει μια τιμή που υποδεικνύει αν η ιδιότητα 'Credential' είναι ίση με την ιδιότητα 'DefaultCredentials'. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | Λαμβάνει μια τιμή της κεφαλίδας 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων για υποκατηγορίες. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων για υποκατηγορίες. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν ο πελάτης ακολουθεί τις ανακατευθύνσεις του διακομιστή. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Ορίζει το όνομα της ομάδας σύνδεσης. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Ορίζει έναν χώρο αποθήκευσης που χρησιμοποιείται για την αποθήκευση cookies. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Ορίζει τις πληροφορίες πιστοποίησης. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η αποσυμπίεση είναι ενεργοποιημένη. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η προ-πιστοποίηση είναι ενεργοποιημένη. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Ορίζει πληροφορίες διαμεσολαβητή. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Ορίζει την κωδικοποίηση που χρησιμοποιείται για τις αιτήσεις του πελάτη. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Ορίζει το χρονικό διάστημα αναμονής πριν λήξει το αίτημα. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η κοινή χρήση σύνδεσης είναι ενεργοποιημένη όταν ο πελάτης χρησιμοποιεί πιστοποίηση NTLM. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Ορίζει το URI της υπηρεσίας XML [Web](../../system.web/). |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Ορίζει τη διεύθυνση URL της υπηρεσίας XML [Web](../../system.web/). |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η ιδιότητα 'Credential' είναι ίση με την ιδιότητα 'DefaultCredentials'. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | Ορίζει μια τιμή της κεφαλίδας 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα πρότυπου ως αδυνατισμένο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε χώρους αποθήκευσης σε αδυνατισμένη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την έννοια C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατισμένο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατισμένο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [WebClientProtocol](../webclientprotocol/)
* Χώρος ονομάτων [System::Web::Services::Protocols](../)
* Βιβλιοθήκη [Aspose.Slides](../../)