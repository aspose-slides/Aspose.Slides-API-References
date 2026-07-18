---
title: HttpWebRequest
second_title: Aspose.Slides για την Αναφορά API C++
description: "Αντιπροσωπεύει την αίτηση ιστού HTTP. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη System::SmartPtr και να χρησιμοποιείτε αυτόν τον δείκτη για να το μεταβιβάζετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 274
url: /el/system.net/httpwebrequest/
---
## HttpWebRequest κλάση


Represents the HTTP web request. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [Abort](./abort/)() override | Ακυρώνει την τρέχουσα αίτηση. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Προσθέτει την κεφαλίδα 'Range' στην τρέχουσα αίτηση. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Προσθέτει την κεφαλίδα 'Range' στην τρέχουσα αίτηση. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Ξεκινά μια ασύγχρονη λειτουργία για λήψη ροής για εγγραφή δεδομένων στον πόρο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Ξεκινά μια ασύγχρονη αίτηση για τον πόρο. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Δημιουργεί μια νέα παρουσία της κλάσης [WebRequest](../webrequest/) χρησιμοποιώντας το καθορισμένο URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Δημιουργεί μια νέα παρουσία της κλάσης [WebRequest](../webrequest/) χρησιμοποιώντας το καθορισμένο URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Δημιουργεί ένα [WebRequest](../webrequest/) απόγονο για το καθορισμένο σχήμα URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Δημιουργεί μια νέα παρουσία της κλάσης [WebRequest](../webrequest/) χρησιμοποιώντας το καθορισμένο URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Δημιουργεί μια νέα παρουσία της κλάσης [WebRequest](../webrequest/) χρησιμοποιώντας το καθορισμένο URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Περιμένει μέχρι η καθορισμένη ασύγχρονη λειτουργία λήψης ροής να ολοκληρωθεί. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Περιμένει μέχρι η καθορισμένη ασύγχρονη αίτηση για τον πόρο να ολοκληρωθεί. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Λαμβάνει την τιμή της κεφαλίδας HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν η αίτηση πρέπει να ακολουθήσει ανακατευθύνσεις. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα που λαμβάνονται από τον πόρο πρέπει να αποθηκευτούν σε προσωρινή μνήμη. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν η προσωρινή μνήμη είναι ενεργή για την αποστολή δεδομένων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Λαμβάνει την πολιτική προσωρινής μνήμης. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Λαμβάνει τη συλλογή των πιστοποιητικών που σχετίζονται με την τρέχουσα αίτηση. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Λαμβάνει το όνομα της ομάδας σύνδεσης. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Λαμβάνει τον αριθμό των byte των δεδομένων αίτησης προς αποστολή. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Λαμβάνει τον τύπο MIME της αίτησης. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Λαμβάνει ένα χρονικό όριο αναμονής μέχρι να ληφθεί ο κωδικός κατάστασης 100-Continue. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Λαμβάνει ένα κοντέινερ cookie που συσχετίζεται με την τρέχουσα αίτηση ιστού. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Λαμβάνει πληροφορίες πιστοποίησης που σχετίζονται με την τρέχουσα αίτηση. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Λαμβάνει τον παγκόσμιο διακομιστή μεσολάβησης HTTP. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν ελήφθη μια απάντηση. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Λαμβάνει τη συλλογή των κεφαλίδων HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν η τρέχουσα αίτηση πρέπει να περιέχει την κεφαλίδα 'Keep-Alive'. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Λαμβάνει το μέγιστο επιτρεπτό αριθμό ανακατευθύνσεων. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Λαμβάνει τη μέθοδο HTTP. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Λαμβάνει μια τιμή που υποδεικνύει εάν η αίτηση πρέπει να προ-πιστοποιηθεί. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Λαμβάνει τη λίστα προθέματος. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Λαμβάνει το διακομιστή μεσολάβησης HTTP. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Λαμβάνει την τιμή της κεφαλίδας 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Επιστρέφει το URI της αίτησης. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα πρέπει να αποστέλλονται σε τμήματα. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Επιστρέφει ένα σημείο υπηρεσίας που αντιπροσωπεύει τη δικτυακή σύνδεση με τον πόρο. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν η τρέχουσα αίτηση μπορεί να χρησιμοποιήσει κοντέινερ cookie. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Λαμβάνει ένα διάστημα χρόνου σε χιλιοστά του δευτερολέπτου μετά το οποίο η αίτηση θα λήξει. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Λαμβάνει μια τιμή που υποδεικνύει εάν η ιδιότητα 'Credential' είναι ίση με την ιδιότητα 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Λαμβάνει την τιμή της κεφαλίδας 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή κατακερματισμού προσαρμοσμένων αντικειμένων. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Επιστρέφει τη ροή για εγγραφή δεδομένων στον πόρο. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Επιστρέφει την απάντηση ιστού που σχετίζεται με την τρέχουσα αίτηση ιστού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Δημιουργεί μια νέα παρουσία. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουράς [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατα αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Καταχωρίζει το [WebRequest](../webrequest/) απόγονο για το καθορισμένο URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Ορίζει την τιμή της κεφαλίδας HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η αίτηση πρέπει να ακολουθήσει ανακατευθύνσεις. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν τα δεδομένα που λαμβάνονται από τον πόρο πρέπει να αποθηκευτούν σε προσωρινή μνήμη. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η προσωρινή μνήμη είναι ενεργή για την αποστολή δεδομένων. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Ορίζει την πολιτική προσωρινής μνήμης. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Ορίζει τη συλλογή των πιστοποιητικών που σχετίζονται με την τρέχουσα αίτηση. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Ορίζει το όνομα της ομάδας σύνδεσης. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Ορίζει τον αριθμό των byte των δεδομένων αίτησης προς αποστολή. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Ορίζει τον τύπο MIME της αίτησης. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Ορίζει ένα χρονικό όριο αναμονής μέχρι να ληφθεί ο κωδικός κατάστασης 100-Continue. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Ορίζει ένα κοντέινερ cookie που σχετίζεται με την τρέχουσα αίτηση ιστού. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Ορίζει πληροφορίες πιστοποίησης που σχετίζονται με την τρέχουσα αίτηση. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Ορίζει τον παγκόσμιο διακομιστή μεσολάβησης HTTP. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Ορίζει τη συλλογή των κεφαλίδων HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν η τρέχουσα αίτηση πρέπει να περιέχει την κεφαλίδα 'Keep-Alive'. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Ορίζει το μέγιστο επιτρεπτό αριθμό ανακατευθύνσεων. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Ορίζει τη μέθοδο HTTP. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν η αίτηση πρέπει να προ-πιστοποιηθεί. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Ορίζει τη λίστα προθέματος. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Ορίζει την έκδοση του HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Ορίζει το διακομιστή μεσολάβησης HTTP. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Ορίζει την τιμή της κεφαλίδας 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν τα δεδομένα πρέπει να αποστέλλονται σε τμήματα. |
| void [set_Timeout](./set_timeout/)(int) override | Ορίζει ένα διάστημα χρόνου σε χιλιοστά του δευτερολέπτου μετά το οποίο η αίτηση θα λήξει. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Ορίζει ένα διάστημα χρόνου σε χιλιοστά του δευτερολέπτου μετά το οποίο η αίτηση θα λήξει. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν η ιδιότητα 'Credential' είναι ίση με την ιδιότητα 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Ορίζει την τιμή της κεφαλίδας 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τον κατασκευαστή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουράς [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [WebRequest](../webrequest/)
* Χώρος ονομάτων [System::Net](../)
* Βιβλιοθήκη [Aspose.Slides](../../)