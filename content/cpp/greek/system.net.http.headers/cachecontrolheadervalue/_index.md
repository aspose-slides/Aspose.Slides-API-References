---
title: CacheControlHeaderValue
second_title: Aspose.Slides για C++ - Αναφορά API
description: "Αντιπροσωπεύει μια τιμή της κεφαλίδας 'Cache-Control'. Τα αντικείμενα αυτής της κλάσης πρέπει να κατασκευάζονται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτή την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 14
url: /el/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue κλάση

Αντιπροσωπεύει μια τιμή της κεφαλίδας 'Cache-Control'. Τα αντικείμενα αυτής της κλάσης πρέπει να κατασκευάζονται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτή την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Δημιουργεί ένα νέο στιγμιότυπο. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Επιστρέφει τη συλλογή των διακριτικών επέκτασης προσωρινής μνήμης. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Λαμβάνει τη μέγιστη τιμή ηλικίας σε δευτερόλεπτα που καθορίζει το χρονικό διάστημα κατά το οποίο ο πελάτης θα αποδεχτεί μια απάντηση. |
| **bool** [get_MaxStale](./get_maxstale/)() | Λαμβάνει την τιμή που καθορίζει αν ο πελάτης θα αποδεχτεί τις ληγμένες απαντήσεις. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Λαμβάνει την τιμή σε δευτερόλεπτα που καθορίζει το χρονικό διάστημα κατά το οποίο ο πελάτης θα αποδεχτεί τις ληγμένες απαντήσεις. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Λαμβάνει την τιμή που καθορίζει τη διάρκεια φρεσκάδας. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Λαμβάνει την τιμή που καθορίζει αν ο διακομιστής απαιτεί επαλήθευση μιας καταχώρισης προσωρινής μνήμης όταν αυτή γίνει παλιά. |
| **bool** [get_NoCache](./get_nocache/)() | Λαμβάνει την τιμή που καθορίζει αν ο πελάτης θα αποδεχτεί μια αποθηκευμένη απόκριση. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Λαμβάνει τη συλλογή των ονομάτων πεδίων στην οδηγία 'no-cache' της κεφαλίδας 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Λαμβάνει την τιμή που καθορίζει αν μια προσωρινή μνήμη δεν πρέπει να αποθηκεύει κανένα μέρος ενός αιτήματος ή απόκρισης HTTP. |
| **bool** [get_NoTransform](./get_notransform/)() | Λαμβάνει την τιμή που καθορίζει αν μια προσωρινή μνήμη ή διακομιστής μεσολάβησης δεν πρέπει να αλλάξει κανένα μέρος του σώματος της οντότητας. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Λαμβάνει την τιμή που καθορίζει αν ο πελάτης πρέπει να χρησιμοποιεί μόνο αποθηκευμένες εγγραφές. |
| **bool** [get_Private](./get_private/)() | Λαμβάνει την τιμή που καθορίζει αν το μήνυμα απόκρισης HTTP ή το μέρος του προορίζεται για έναν μόνο χρήστη και δεν πρέπει να αποθηκεύεται από κοινόχρηστη προσωρινή μνήμη. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Λαμβάνει τη συλλογή των ονομάτων πεδίων στην οδηγία 'private' της κεφαλίδας 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Λαμβάνει την τιμή που καθορίζει αν ο διακομιστής απαιτεί επαλήθευση μιας καταχώρισης προσωρινής μνήμης όταν αυτή γίνει παλιά για τις κοινόχρηστες προσωρινές μνήμες του πράκτορα χρήστη. |
| **bool** [get_Public](./get_public/)() | Λαμβάνει την τιμή που καθορίζει αν μια απόκριση HTTP μπορεί να αποθηκευτεί από οποιαδήποτε προσωρινή μνήμη. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Λαμβάνει την κοινόχρηστη μέγιστη τιμή ηλικίας σε δευτερόλεπτα που παρακάμπτει την οδηγία 'max-age' στην κεφαλίδα 'Cache-Control' ή την κεφαλίδα 'Expires' για μια κοινόχρηστη προσωρινή μνήμη. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Μετατρέπει μια δοθείσα συμβολοσειρά από τον καθορισμένο δείκτη σε ένα στιγμιότυπο της κλάσης [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρός [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Μετατρέπει μια δοθείσα συμβολοσειρά σε ένα στιγμιότυπο της κλάσης [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ορίζει τη μέγιστη τιμή ηλικίας σε δευτερόλεπτα που καθορίζει το χρονικό διάστημα κατά το οποίο ο πελάτης θα αποδεχτεί μια απάντηση. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Ορίζει την τιμή που καθορίζει αν ο πελάτης θα αποδεχτεί τις ληγμένες απαντήσεις. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ορίζει την τιμή σε δευτερόλεπτα που καθορίζει το χρονικό διάστημα κατά το οποίο ο πελάτης θα αποδεχτεί τις ληγμένες απαντήσεις. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ορίζει την τιμή που καθορίζει τη διάρκεια φρεσκάδας. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Ορίζει την τιμή που καθορίζει αν ο διακομιστής απαιτεί επαλήθευση μιας καταχώρισης προσωρινής μνήμης όταν αυτή γίνει παλιά. |
| void [set_NoCache](./set_nocache/)(**bool**) | Ορίζει την τιμή που καθορίζει αν ο πελάτης θα αποδεχτεί μια αποθηκευμένη απόκριση. |
| void [set_NoStore](./set_nostore/)(**bool**) | Ορίζει την τιμή που καθορίζει αν μια προσωρινή μνήμη δεν πρέπει να αποθηκεύει κανένα μέρος ενός αιτήματος ή απόκρισης HTTP. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Ορίζει την τιμή που καθορίζει αν μια προσωρινή μνήμη ή διακομιστής μεσολάβησης δεν πρέπει να αλλάξει κανένα μέρος του σώματος της οντότητας. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Ορίζει την τιμή που καθορίζει αν ο πελάτης πρέπει να χρησιμοποιεί μόνο αποθηκευμένες εγγραφές. |
| void [set_Private](./set_private/)(**bool**) | Ορίζει την τιμή που καθορίζει αν το μήνυμα απόκρισης HTTP ή το μέρος του προορίζεται για έναν μόνο χρήστη και δεν πρέπει να αποθηκευτεί από κοινόχρηστη προσωρινή μνήμη. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Ορίζει την τιμή που καθορίζει αν ο διακομιστής απαιτεί επαλήθευση μιας καταχώρισης προσωρινής μνήμης όταν αυτή γίνει παλιά για τις κοινόχρηστες προσωρινές μνήμες του πράκτορα χρήστη. |
| void [set_Public](./set_public/)(**bool**) | Ορίζει την τιμή που καθορίζει αν μια απόκριση HTTP μπορεί να αποθηκευτεί από οποιαδήποτε προσωρινή μνήμη. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ορίζει τη κοινόχρηστη μέγιστη τιμή ηλικίας σε δευτερόλεπτα που παρακάμπτει την οδηγία 'max-age' στην κεφαλίδα 'Cache-Control' ή την κεφαλίδα 'Expires' για μια κοινόχρηστη προσωρινή μνήμη. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδυνατό τρόπο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Προσπαθεί να μετατρέψει μια δοθείσα συμβολοσειρά σε ένα στιγμιότυπο της κλάσης [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρός [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατό μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατό μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ICloneable](../../system/icloneable/)
* Χώρος ονομάτων [System::Net::Http::Headers](../)
* Βιβλιοθήκη [Aspose.Slides](../../)