---
title: XmlSchemaSimpleType
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει το στοιχείο simpleType για απλό περιεχόμενο από το XML Schema όπως ορίζεται από το Παγκόσμιο Συμβούλιο Διαδικτύου (W3C). Αυτή η κλάση ορίζει έναν απλό τύπο. Οι απλοί τύποι μπορούν να καθορίζουν πληροφορίες και περιορισμούς για την τιμή των γνωρισμάτων ή των στοιχείων με περιεχόμενο μόνο κειμένου.
type: docs
weight: 833
url: /el/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType κλάση

Αναπαριστά το στοιχείο **simpleType** για απλό περιεχόμενο από XML [Schema](../) όπως ορίζεται από το Παγκόσμιο Συμβούλιο [Web](../../system.web/) (W3C). Αυτή η κλάση ορίζει έναν απλό τύπο. Οι απλοί τύποι μπορούν να καθορίζουν πληροφορίες και περιορισμούς για την τιμή των γνωρισμάτων ή των στοιχείων με κείμενο μόνο.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομείωση σύγκρισης κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομείωση σύγκρισης κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Επιστρέφει την ιδιότητα **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | Επιστρέφει τον τύπο αντικειμένου μετά τη μεταγλώττιση ή τον ενσωματωμένο τύπο δεδομένων XML [Schema](../) Definition Language (XSD), στοιχείο simpleType ή στοιχείο complexType. Αυτή είναι μια τιμή infoset μετά τη μεταγλώττιση σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση για τον βασικό τύπο αυτού του τύπου σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\> [get_Content](./get_content/)() | Επιστρέφει ένα από τα [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) ή [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση για τον τύπο δεδομένων του σύνθετου τύπου. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | Επιστρέφει πληροφορίες μετά τη μεταγλώττιση για το πώς αυτό το στοιχείο προήλθε από τον βασικό του τύπο. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | Επιστρέφει το τελικό χαρακτηριστικό της παραγώγησης τύπου που δείχνει αν επιτρέπονται περαιτέρω παραγώγεις. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | Επιστρέφει την ερμηνεία μετά τη μεταγλώττιση της τιμής [XmlSchemaType::get_Final](../xmlschematype/get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Επιστρέφει το αναγνωριστικό συμβολοσειράς. |
| virtual **bool** [get_IsMixed](../xmlschematype/get_ismixed/)() | Επιστρέφει τιμή που υποδεικνύει αν αυτός ο τύπος έχει μειχόμενο μοντέλο περιεχομένου. Η κλήση αυτή είναι έγκυρη μόνο σε σύνθετο τύπο. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Επιστρέφει τον αριθμό γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Επιστρέφει τη θέση γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | Επιστρέφει το όνομα του τύπου. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Επιστρέφει το XmlSerializerNamespaces που θα χρησιμοποιηθεί με αυτό το αντικείμενο σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Επιστρέφει το γονικό του [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | Επιστρέφει το πλήρως διακριτό όνομα για τον τύπο που χτίστηκε από το χαρακτηριστικό **Name** του τύπου. Αυτή είναι μια τιμή μετά τη μεταγλώττιση σχήματος. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Επιστρέφει την πηγή τοποθεσίας για το αρχείο που φόρτωσε το σχήμα. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | Επιστρέφει το XmlTypeCode του τύπου. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Επιστρέφει τα πλήρως διακριτά χαρακτηριστικά που δεν ανήκουν στο τρέχον namespace στόχο του σχήματος. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Επιστρέφει ένα [XmlSchemaComplexType](../xmlschemacomplextype/) που αντιπροσωπεύει τον ενσωματωμένο σύνθετο τύπο του καθορισμένου σύνθετου τύπου. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Επιστρέφει ένα [XmlSchemaComplexType](../xmlschemacomplextype/) που αντιπροσωπεύει τον ενσωματωμένο σύνθετο τύπο του καθορισμένου σύνθετου τύπου με πλήρως διακριτό όνομα. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Επιστρέφει ένα [XmlSchemaSimpleType](./) που αντιπροσωπεύει τον ενσωματωμένο απλό τύπο του απλού τύπου που καθορίζεται από το πλήρως διακριτό όνομα. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Επιστρέφει ένα [XmlSchemaSimpleType](./) που αντιπροσωπεύει τον ενσωματωμένο απλό τύπο του καθορισμένου απλού τύπου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# «is». |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Επιστρέφει τιμή που υποδεικνύει αν ο δηλωμένος τύπος σχήματος είναι παράγωγος του δηλωμένου βασικού τύπου σχήματος. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην ουσία, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην ουσία, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγορίων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστης αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Ορίζει την ιδιότητα **annotation**. |
| void [set_Content](./set_content/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\>\&) | Ορίζει ένα από τα [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) ή [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Ορίζει το τελικό χαρακτηριστικό της παραγώγησης τύπου που δείχνει αν επιτρέπονται περαιτέρω παραγώγεις. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Ορίζει το αναγνωριστικό συμβολοσειράς. |
| virtual void [set_IsMixed](../xmlschematype/set_ismixed/)(**bool**) | Ορίζει τιμή που υποδεικνύει αν αυτός ο τύπος έχει μειχόμενο μοντέλο περιεχομένου. Η κλήση αυτή είναι έγκυρη μόνο σε σύνθετο τύπο. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Ορίζει τον αριθμό γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Ορίζει τη θέση γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | Ορίζει το όνομα του τύπου. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Ορίζει το XmlSerializerNamespaces που θα χρησιμοποιηθεί με αυτό το αντικείμενο σχήματος. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Ορίζει το γονικό του [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Ορίζει την πηγή τοποθεσίας για το αρχείο που φόρτωσε το σχήμα. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Ορίζει τα πλήρως διακριτά χαρακτηριστικά που δεν ανήκουν στο τρέχον namespace στόχο του σχήματος. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaSimpleType](./xmlschemasimpletype/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlSchemaSimpleType](./). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Typedef | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινόχρηστο δείκτη σε ένα στιγμιότυπο αυτής της κλάσης. |

## Παρατηρήσεις

Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο μέσω της συνάρτησης [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπα αυτού του τύπου στη στοίβα ή μέσω του τελεστή new, διότι θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα διαβεβαίωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε ως όρισμα σε συναρτήσεις. 

## Δείτε επίσης

* Κλάση [XmlSchemaType](../xmlschematype/)
* Χώρος ονομάτων [System::Xml::Schema](../)
* Βιβλιοθήκη [Aspose.Slides](../../)