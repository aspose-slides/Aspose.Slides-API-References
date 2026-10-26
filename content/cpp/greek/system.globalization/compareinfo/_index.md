---
title: CompareInfo
second_title: Aspose.Slides για C++ Αναφορά API
description: "Δημιουργεί σύγκριση συμβολοσειρών ευαίσθητη στον πολιτισμό. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκληθούν σφάλματα χρόνου εκτέλεσης και/ή σφαλματα επιβεβαίωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr pointer και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε functions as argument."
type: docs
weight: 40
url: /el/system.globalization/compareinfo/
---
## CompareInfo κλάση

Δημιουργεί σύγκριση συμβολοσειρών ευαίσθητη στον πολιτισμό. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφαλματα επιβεβαίωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα.

```cpp
class CompareInfo : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Συγκρίνει συμβολοσειρές. Δεν έχει υλοποιηθεί. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Συγκρίνει συμβολοσειρές. Υποστηρίζονται μόνο οι λειτουργίες Ordinal και OrdinalIgnoreCase. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | Συγκρίνει τμήμα μιας συμβολοσειράς με τμήμα δεύτερης συμβολοσειράς. Δεν έχει υλοποιηθεί. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Συγκρίνει το τελευταίο τμήμα μιας συμβολοσειράς με το τελευταίο τμήμα της δεύτερης συμβολοσειράς χρησιμοποιώντας μεθόδους σύγκρισης συμβολοσυρροών. Δεν έχει υλοποιηθεί. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | Συγκρίνει το τελευταίο τμήμα μιας συμβολοσειράς με το τελευταίο τμήμα της δεύτερης συμβολοσειράς. Δεν έχει υλοποιηθεί. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Συγκρίνει τμήμα μιας συμβολοσειράς με τμήμα δεύτερης συμβολοσειράς χρησιμοποιώντας μεθόδους σύγκρισης συμβολοσυρροών. Δεν έχει υλοποιηθεί. |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | Πληροφορίες RTTI. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| int [get_LCID](./get_lcid/)() const | Λαμβάνει το LCID του πολιτισμού που συνδέεται με τον συγκριτή. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Λαμβάνει το όνομα του πολιτισμού που συνδέεται με τον συγκριτή. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | Λαμβάνει πληροφορίες σχετικά με την έκδοση ταξινόμησης. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Λαμβάνει [CompareInfo](./) που σχετίζεται με τον καθορισμένο πολιτισμό και χρησιμοποιεί μεθόδους σύγκρισης συμβολοσυρροών στην καθορισμένη συναρμολόγηση. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Λαμβάνει [CompareInfo](./) που σχετίζεται με τον καθορισμένο πολιτισμό και χρησιμοποιεί μεθόδους σύγκρισης συμβολοσυρροών στην καθορισμένη συναρμολόγηση. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | Λαμβάνει [CompareInfo](./) που σχετίζεται με τον καθορισμένο πολιτισμό. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | Λαμβάνει [CompareInfo](./) που σχετίζεται με τον καθορισμένο πολιτισμό. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Λαμβάνει κωδικό κατακερματισμού συμβολοσειράς βασισμένο στις καθορισμένες επιλογές σύγκρισης. |
| int [GetHashCode](./gethashcode/)() const override | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τον κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Λαμβάνει το αντικείμενο [SortKey](../sortkey/) για τη συγκεκριμένη συμβολοσειρά χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | Λαμβάνει το αντικείμενο [SortKey](../sortkey/) για τη συγκεκριμένη συμβολοσειρά. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Αναζητά υποσυμβολοσειρά. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Αναζητά υποσυμβολοσειρά. Υποστηρίζεται μόνο η λειτουργία Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Αναζητά υποσυμβολοσειρά. Υποστηρίζεται μόνο η λειτουργία Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Αναζητά τον καθορισμένο χαρακτήρα. Υποστηρίζεται μόνο η λειτουργία Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Αναζητά υποσυμβολοσειρά. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | Αναζητά τον καθορισμένο χαρακτήρα. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Αναζητά υποσυμβολοσειρά. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Αναζητά τον καθορισμένο χαρακτήρα. Υποστηρίζεται μόνο η λειτουργία Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Αναζητά τον καθορισμένο χαρακτήρα. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | Αναζητά τον καθορισμένο χαρακτήρα. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Αναζητά υποσυμβολοσειρά. Υποστηρίζεται μόνο η λειτουργία Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Αναζητά τον καθορισμένο χαρακτήρα. Υποστηρίζεται μόνο η λειτουργία Ordinal. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αποτελεί μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Ελέγχει εάν η καθορισμένη συμβολοσειρά αρχίζει με το καθορισμένο πρόθεμα χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Ελέγχει εάν η καθορισμένη συμβολοσειρά αρχίζει με το καθορισμένο πρόθεμα. |
| static **bool** [IsSortable](./issortable/)(char16_t) | Ελέγχει εάν ένας καθορισμένος χαρακτήρας μπορεί να ταξινομηθεί. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | Ελέγχει εάν μια καθορισμένη συμβολοσειρά μπορεί να ταξινομηθεί. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Ελέγχει εάν η καθορισμένη συμβολοσειρά τελειώνει με το καθορισμένο επίθημα χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Ελέγχει εάν η καθορισμένη συμβολοσειρά τελειώνει με το καθορισμένο επίθημα. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Αναζητά την τελευταία εμφάνιση της καθορισμένης υποσυμβολοσειράς. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Αναζητά την τελευταία εμφάνιση της καθορισμένης υποσυμβολοσειράς χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Αναζητά την τελευταία εμφάνιση του καθορισμένου χαρακτήρα χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Αναζητά την τελευταία εμφάνιση της καθορισμένης συμβολοσειράς. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Αναζητά την τελευταία εμφάνιση της καθορισμένης συμβολοσειράς χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Αναζητά την τελευταία εμφάνιση του καθορισμένου χαρακτήρα χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Αναζητά την τελευταία εμφάνιση της καθορισμένης συμβολοσειράς. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | Αναζητά την τελευταία εμφάνιση του καθορισμένου χαρακτήρα. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Αναζητά την τελευταία εμφάνιση της καθορισμένης συμβολοσειράς χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Αναζητά την τελευταία εμφάνιση του καθορισμένου χαρακτήρα χρησιμοποιώντας τις καθορισμένες επιλογές σύγκρισης. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | Αναζητά την τελευταία εμφάνιση του καθορισμένου χαρακτήρα. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Αναζητά την τελευταία εμφάνιση του καθορισμένου χαρακτήρα. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτικού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγορίων. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει την n'tη παράμετρο προτύπου ως αδυναμικό δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο εποπτικού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδυναμικών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδυναμικών αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)