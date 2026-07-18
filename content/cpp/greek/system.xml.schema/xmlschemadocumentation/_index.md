---
title: XmlSchemaDocumentation
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αντιπροσωπεύει το στοιχείο documentation από το XML Schema, όπως καθορίζεται από το World Wide Web Consortium (W3C). Αυτή η κλάση καθορίζει πληροφορίες που προορίζονται για ανάγνωση ή χρήση από ανθρώπους μέσα σε μια σημείωση.
type: docs
weight: 352
url: /el/system.xml.schema/xmlschemadocumentation/
---
## XmlSchemaDocumentation κλάση

Represents the **documentation** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class specifies information to be read or used by humans within an **annotation**.

```cpp
class XmlSchemaDocumentation : public System::Xml::Schema::XmlSchemaObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει συγκριτική λειτουργία κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει συγκριτική λειτουργία κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [String](../../system/string/) [get_Language](./get_language/)() | Επιστρέφει το χαρακτηριστικό **xml:lang**. Αυτό λειτουργεί ως ένδειξη της γλώσσας που χρησιμοποιείται στα περιεχόμενα. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Επιστρέφει τον αριθμό γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Επιστρέφει τη θέση γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../../system.xml/xmlnode/)\>\> [get_Markup](./get_markup/)() | Επιστρέφει έναν πίνακα αντικειμένων [XmlNode](../../system.xml/xmlnode/) που αντιπροσωπεύει τους κόμβους-παιδιά της τεκμηρίωσης. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Επιστρέφει το XmlSerializerNamespaces για χρήση με αυτό το αντικείμενο σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Επιστρέφει τον γονέα αυτού του [XmlSchemaObject](../xmlschemaobject/). |
| [String](../../system/string/) [get_Source](./get_source/)() | Επιστρέφει την πηγή Uniform Resource Identifier (URI) των πληροφοριών. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Επιστρέφει την τοποθεσία προέλευσης του αρχείου που φόρτωσε το σχήμα. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εκτελεί τη δήλωση κλειδώματος C# lock(). Καλέστε το άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Language](./set_language/)(const [String](../../system/string/)\&) | Ορίζει το χαρακτηριστικό **xml:lang**. Αυτό λειτουργεί ως ένδειξη της γλώσσας που χρησιμοποιείται στα περιεχόμενα. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Ορίζει τον αριθμό γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Ορίζει τη θέση γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_Markup](./set_markup/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../../system.xml/xmlnode/)\>\>\&) | Ορίζει έναν πίνακα αντικειμένων [XmlNode](../../system.xml/xmlnode/) που αντιπροσωπεύει τους κόμβους-παιδιά της τεκμηρίωσης. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Ορίζει το XmlSerializerNamespaces για χρήση με αυτό το αντικείμενο σχήματος. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Ορίζει τον γονέα αυτού του [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Source](./set_source/)(const [String](../../system/string/)\&) | Ορίζει την πηγή Uniform Resource Identifier (URI) των πληροφοριών. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Ορίζει την τοποθεσία προέλευσης του αρχείου που φόρτωσε το σχήμα. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει το κατασκευαστικό τύπο C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εκτελεί την απελευθέρωση της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να καλείται άμεσα· αντ' αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη σε ένα στιγμιότυπο αυτής της κλάσης. |

## Παρατηρήσεις

Τα αντικείμενα αυτής της κλάσης θα πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπα αυτού του τύπου στο στοίβα ή με τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτό το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα. 

## Δείτε επίσης

* Κλάση [XmlSchemaObject](../xmlschemaobject/)
* Χώρος ονομάτων [System::Xml::Schema](../)
* Βιβλιοθήκη [Aspose.Slides](../../)