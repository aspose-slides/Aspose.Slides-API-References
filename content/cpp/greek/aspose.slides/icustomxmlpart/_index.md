---
title: ICustomXmlPart
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά προσαρμοσμένο τμήμα xml.
type: docs
weight: 1925
url: /el/aspose.slides/icustomxmlpart/
---
## ICustomXmlPart κλάση

Αναπαριστά προσαρμοσμένο τμήμα XML.

```cpp
class ICustomXmlPart : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδείξης σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδείξης σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::Guid](../../system/guid/) [get_ItemId](./get_itemid/)() | Καθορίζει έναν παγκοσμίως μοναδικό αναγνωριστικό (GUID) που ταυτοποιεί μοναδικά ένα προσαρμοσμένο τμήμα XML μέσα σε ένα έγγραφο Office Open XML. Μόνο για ανάγνωση [System::Guid](../../system/guid/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_NamespaceSchemas](./get_namespaceschemas/)() | Επιστρέφει τα σχήματα XML της συλλογής που σχετίζονται με το προσαρμοσμένο τμήμα XML. Μόνο για ανάγνωση [System::String](../../system/string/)[]. |
| virtual [System::String](../../system/string/) [get_XmlAsString](./get_xmlasstring/)() | Επιστρέφει τα δεδομένα XML ως συμβολοσειρά UTF-8. Ανάγνωση [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_XmlData](./get_xmldata/)() | Επιστρέφει τα δεδομένα XML. Ανάγνωση **uint8_t**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την κατακερματισμένη αποτύπωση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αποτελεί παράδειγμα του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση C# lock() για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής αντιστοίχισης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική έκδοση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική έκδοση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| virtual void [Remove](./remove/)() | Αφαιρεί το προσαρμοσμένο τμήμα XML από την παρουσίαση. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_ItemId](./set_itemid/)([System::Guid](../../system/guid/)) | Καθορίζει έναν παγκοσμίως μοναδικό αναγνωριστικό (GUID) που ταυτοποιεί μοναδικά ένα προσαρμοσμένο τμήμα XML μέσα σε ένα έγγραφο Office Open XML. Μόνο για ανάγνωση [System::Guid](../../system/guid/). |
| virtual void [set_XmlAsString](./set_xmlasstring/)([System::String](../../system/string/)) | Ορίζει τα δεδομένα XML ως συμβολοσειρά UTF-8. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_XmlData](./set_xmldata/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ορίζει τα δεδομένα XML. Εγγραφή **uint8_t**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί του, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί τη δήλωση C# lock() για άρση κλειδώματος. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)