---
title: HttpRequestCachePolicy
second_title: Aspose.Slides για την Αναφορά API του C++
description: "Πολιτική προσωρινής αποθήκευσης HTTP που εκφράζει τη σημασιολογία προσωρινής αποθήκευσης RFC2616. Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject(). Ποτέ μην δημιουργείτε αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα επιβεβαίωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε ως όρισμα σε συναρτήσεις."
type: docs
weight: 1
url: /el/system.net.cache/httprequestcachepolicy/
---
## HttpRequestCachePolicy κλάση

HTTP cache policy that expresses RFC2616 HTTP caching semantic. Objects of this κλάση should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this κλάση into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpRequestCachePolicy : public System::Net::Cache::RequestCachePolicy
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει την C#-στυλ σύγκριση αριθμών κινητής υποδιαστολής όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει την C#-στυλ σύγκριση αριθμών κινητής υποδιαστολής όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [DateTime](../../system/datetime/) [get_CacheSyncDate](./get_cachesyncdate/)() const | Λαμβάνει τον χρόνο που οι πόροι αποθηκευμένοι στην κρυφή μνήμη πρέπει να επαληθευτούν. |
| [DateTime](../../system/datetime/) [get_InternalCacheSyncDateUtc](./get_internalcachesyncdateutc/)() const | Λαμβάνει τον χρόνο σε μορφή UTC που οι πόροι αποθηκευμένοι στην κρυφή μνήμη πρέπει να επαληθευτούν. Για εσωτερική χρήση μόνο. |
| [HttpRequestCacheLevel](../httprequestcachelevel/) [get_Level](./get_level/)() const | Λαμβάνει την καθορισμένη τιμή HttpRequestCacheLevel. |
| [RequestCacheLevel](../requestcachelevel/) [get_Level](../requestcachepolicy/get_level/)() | Λαμβάνει την καθορισμένη τιμή RequestCacheLevel. |
| [TimeSpan](../../system/timespan/) [get_MaxAge](./get_maxage/)() const | Λαμβάνει το μέγιστο επιτρεπτό ηλικιακό διάστημα για έναν πόρο. |
| [TimeSpan](../../system/timespan/) [get_MaxStale](./get_maxstale/)() const | Λαμβάνει τη μέγιστη τιμή σήμανσης ως παλιό (staleness) που επιτρέπεται για έναν πόρο. |
| [TimeSpan](../../system/timespan/) [get_MinFresh](./get_minfresh/)() const | Λαμβάνει το ελάχιστο επιτρεπτό ηλικιακό διάστημα για έναν πόρο. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)() | Δημιουργεί μια νέα παρουσία. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpRequestCacheLevel](../httprequestcachelevel/)) | Δημιουργεί μια νέα παρουσία. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/)) | Δημιουργεί μια νέα παρουσία. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/)) | Δημιουργεί μια νέα παρουσία. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([DateTime](../../system/datetime/)) | Δημιουργεί μια νέα παρουσία. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/), [DateTime](../../system/datetime/)) | Δημιουργεί μια νέα παρουσία. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμετρο αναφοράς κατά την καθορισμένη τιμή. |
|  [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)() | Δημιουργεί μια νέα παρουσία. |
|  [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)([RequestCacheLevel](../requestcachelevel/)) | Δημιουργεί μια νέα παρουσία με την καθορισμένη τιμή RequestCacheLevel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυνατή αναφορά (αντί για κοινή). Επιτρέπει την αλλαγή των δεικτών σε containers σε αδυνατή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμετρου αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμετρο αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμετρο αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δομή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [RequestCachePolicy](../requestcachepolicy/)
* Χώρος ονομάτων [System::Net::Cache](../)
* Βιβλιοθήκη [Aspose.Slides](../../)