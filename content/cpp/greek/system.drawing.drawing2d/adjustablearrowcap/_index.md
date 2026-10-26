---
title: AdjustableArrowCap
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει μια ρυθμιζόμενη κεφαλή γραμμής σε σχήμα βέλους. Τα αντικείμενα αυτής της κλάσης πρέπει να καταληφθούν μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργήσετε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 1
url: /el/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap κλάση

Αντιπροσωπεύει μια ρυθμιζόμενη κεφαλή γραμμής σε σχήμα βέλους. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργήσετε μια παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | Δημιουργεί μια νέα περίπτωση του [AdjustableArrowCap](./) με το καθορισμένο πλάτος και ύψος. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | Επιστρέφει ένα αντίγραφο του τρέχοντος αντικειμένου. |
|  [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | Δημιουργεί μια νέα περίπτωση της κλάσης [CustomLineCap](../customlinecap/) που αντιπροσωπεύει μια προσαρμοσμένη κεφαλή γραμμής με τις καθορισμένες ιδιότητες. |
| void [Dispose](../customlinecap/dispose/)() | Απελευθερώνει όλους τους πόρους του λειτουργικού συστήματος που αποκτήθηκαν από το τρέχον αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | Επιστρέφει τη βασική κεφαλή γραμμής από την οποία δημιουργείται αυτή η προσαρμοσμένη κεφαλή. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | Επιστρέφει την απόσταση μεταξύ της γραμμής και της κεφαλής. |
| **bool** [get_Filled](./get_filled/)() const | Επιστρέφει μια τιμή που υποδεικνύει αν το βέλος που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι γεμάτο. |
| **float** [get_Height](./get_height/)() const | Επιστρέφει το ύψος του βέλους που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **float** [get_MiddleInset](./get_middleinset/)() const | Ορίζει την απόσταση μεταξύ της γραμμής και της κεφαλής που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | Επιστρέφει την τιμή LineJoin που καθορίζει πώς ενώνονται οι γραμμές αυτής της προσαρμοσμένης κεφαλής. |
| **float** [get_Width](./get_width/)() const | Επιστρέφει το πλάτος του βέλους που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | Επιστρέφει την κλίμακα αυτής της προσαρμοσμένης κεφαλής. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | Λαμβάνει τις αρχικές και τελικές κεφαλές γραμμής της προσαρμοσμένης κεφαλής που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών των υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών των υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | Ορίζει τη βασική τιμή κεφαλής γραμμής για αυτή την προσαρμοσμένη κεφαλή. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | Ορίζει την απόσταση μεταξύ της γραμμής και της κεφαλής. |
| void [set_Filled](./set_filled/)(**bool**) | Ορίζει μια τιμή που καθορίζει αν το βέλος που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι γεμάτο. |
| void [set_Height](./set_height/)(**float**) | Ορίζει το ύψος του βέλους που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | Ορίζει την απόσταση μεταξύ της γραμμής και της κεφαλής που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | Ορίζει την τιμή LineJoin που καθορίζει πώς ενώνονται οι γραμμές αυτής της προσαρμοσμένης κεφαλής. |
| void [set_Width](./set_width/)(**float**) | Ορίζει το πλάτος του βέλους που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | Ορίζει την κλίμακα αυτής της προσαρμοσμένης κεφαλής. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | Ορίζει τις αρχικές και τελικές κεφαλές γραμμής της προσαρμοσμένης κεφαλής που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [CustomLineCap](../customlinecap/)
* Χώρος ονομάτων [System::Drawing::Drawing2D](../)
* Βιβλιοθήκη [Aspose.Slides](../../)