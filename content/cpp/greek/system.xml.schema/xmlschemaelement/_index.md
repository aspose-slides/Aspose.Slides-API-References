---
title: XmlSchemaElement
second_title: Aspose.Slides για αναφορά API C++
description: Αντιπροσωπεύει το στοιχείο element από το XML Schema όπως ορίζεται από το Παγκόσμιο Ιδρυμα Ιστού (W3C). Αυτή η κλάση είναι η βασική κλάση για όλους τους τύπους σωματιδίων και χρησιμοποιείται για την περιγραφή ενός στοιχείου σε ένα έγγραφο XML.
type: docs
weight: 365
url: /el/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement κλάση


Αναπαριστά το στοιχείο **element** από το XML [Schema](../) όπως καθορίζεται από το Παγκόσμιο [Web](../../system.web/) Consortium (W3C). Αυτή η κλάση είναι η βασική κλάση για όλους τους τύπους σωματιδίων και χρησιμοποιείται για την περιγραφή ενός στοιχείου σε ένα έγγραφο XML.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Επιστρέφει την ιδιότητα **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Επιστρέφει μια παράγωγη **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Επιστρέφει την ερμηνεία μετά τη μεταγλώττιση της τιμής **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Επιστρέφει τη συλλογή περιορισμών στο στοιχείο. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Επιστρέφει την προεπιλεγμένη τιμή του στοιχείου εάν το περιεχόμενό του είναι απλός τύπος ή το περιεχόμενό του είναι **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Επιστρέφει ένα αντικείμενο [XmlSchemaType](../xmlschematype/) που αντιπροσωπεύει τον τύπο του στοιχείου βάσει των τιμών [XmlSchemaElement::get_SchemaType](./get_schematype/) ή [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Επιστρέφει ένα αντικείμενο βάσει του [XmlSchemaElement](./) ή [XmlSchemaElement](./) του στοιχείου, που περιέχει την ερμηνεία μετά τη μεταγλώττιση της τιμής **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Επιστρέφει την τιμή **Final** για ένδειξη ότι δεν επιτρέπεται περαιτέρω παράγωγος. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Επιστρέφει την ερμηνεία μετά τη μεταγλώττιση της τιμής **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Επιστρέφει την σταθερή τιμή. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Επιστρέφει τη μορφή του στοιχείου. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Επιστρέφει το αναγνωριστικό συμβολοσειράς. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Επιστρέφει πληροφορία που δείχνει αν το στοιχείο μπορεί να χρησιμοποιηθεί σε έγγραφο实例. |
| **bool** [get_IsNillable](./get_isnillable/)() | Επιστρέφει πληροφορία που υποδεικνύει αν **xsi:nil** μπορεί να εμφανιστεί στα δεδομένα实例. Δείχνει αν μπορεί να εκχωρηθεί ρητή τιμή nil στο στοιχείο. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Επιστρέφει τον αριθμό γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Επιστέφει τη θέση γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Επιστέφει το μέγιστο αριθμό επαναλήψεων του σωματιδίου. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Επιστέφει τον αριθμό ως συμβολοσειρά. Μέγιστος αριθμός επαναλήψεων του σωματιδίου. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Επιστέφει το ελάχιστο αριθμό επαναλήψεων του σωματιδίου. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Επιστέφει τον αριθμό ως συμβολοσειρά. Ο ελάχιστος αριθμός επαναλήψεων του σωματιδίου. |
| [String](../../system/string/) [get_Name](./get_name/)() | Επιστέφει το όνομα του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Επιστέφει το XmlSerializerNamespaces προς χρήση με αυτό το αντικείμενο σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Επιστέφει το γονέα του [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Επιστέφει το πραγματικό επιπλήκτο όνομα για το δοθέν στοιχείο. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Επιστέφει το όνομα αναφοράς ενός στοιχείου που δηλώνεται σε αυτό το σχήμα (ή σε άλλο σχήμα που υποδεικνύεται από τον καθορισμένο χώρο ονομάτων). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Επιστέφει τον τύπο του στοιχείου. Μπορεί να είναι σύνθετος ή απλός τύπος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Επιστέφει το όνομα ενός ενσωματωμένου τύπου δεδομένων που ορίζεται σε αυτό το σχήμα ή σε άλλο σχήμα που υποδεικνύεται από τον καθορισμένο χώρο ονομάτων. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Επιστέφει τη θέση προέλευσης του αρχείου που φόρτωσε το σχήμα. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Επιστέφει το όνομα ενός στοιχείου που αντικαθίσταται από αυτό το στοιχείο. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Επιστέφει τα επιπλήκτα γνωρίσματα που δεν ανήκουν στο τρέχον χώρο στόχου του σχήματος. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή C# lock() για κλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής εκχώρησης. Δεν αντιγράφει κάτι, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τιμή τύπου με αναφορά με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Ορίζει την ιδιότητα **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Ορίζει μια παράγωγη **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Ορίζει την προεπιλεγμένη τιμή του στοιχείου εάν το περιεχόμενό του είναι απλός τύπος ή το περιεχόμενό του είναι **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Ορίζει την τιμή **Final** για ένδειξη ότι δεν επιτρέπεται περαιτέρω παράγωγος. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Ορίζει τη σταθερή τιμή. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Ορίζει τη μορφή του στοιχείου. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Ορίζει το αναγνωριστικό συμβολοσειράς. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Ορίζει πληροφορία που δείχνει αν το στοιχείο μπορεί να χρησιμοποιηθεί σε έγγραφο实例. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Ορίζει πληροφορία που υποδεικνύει αν **xsi:nil** μπορεί να εμφανιστεί στα δεδομένα实例. Δείχνει αν μπορεί να εκχωρηθεί ρητή τιμή nil στο στοιχείο. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Ορίζει τον αριθμό γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Ορίζει τη θέση γραμμής στο αρχείο στο οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Ορίζει το μέγιστο αριθμό επαναλήψεων του σωματιδίου. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Ορίζει τον αριθμό ως συμβολοσειρά. Μέγιστος αριθμός επαναλήψεων του σωματιδίου. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Ορίζει το ελάχιστο αριθμό επαναλήψεων του σωματιδίου. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Ορίζει τον αριθμό ως συμβολοσειρά. Ο ελάχιστος αριθμός επαναλήψεων του σωματιδίου. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Ορίζει το όνομα του στοιχείου. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Ορίζει το XmlSerializerNamespaces προς χρήση με αυτό το αντικείμενο σχήματος. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Ορίζει το γονέα του [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Ορίζει το όνομα αναφοράς ενός στοιχείου που δηλώνεται σε αυτό το σχήμα (ή σε άλλο σχήμα που υποδεικνύεται από τον καθορισμένο χώρο ονομάτων). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Ορίζει τον τύπο του στοιχείου. Μπορεί να είναι σύνθετος ή απλός τύπος. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Ορίζει το όνομα ενός ενσωματωμένου τύπου δεδομένων που ορίζεται σε αυτό το σχήμα ή σε άλλο σχήμα που υποδεικνύεται από τον καθορισμένο χώρο ονομάτων. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Ορίζει τη θέση προέλευσης του αρχείου που φόρτωσε το σχήμα. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Ορίζει το όνομα ενός στοιχείου που αντικαθίσταται από αυτό το στοιχείο. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Ορίζει τα επιπλήκτα γνωρίσματα που δεν ανήκουν στο τρέχον χώρο στόχου του σχήματος. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα πρότυπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη κατάσταση. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δεικτών ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δεικτών ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκευαστικό C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δεικτών ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δεικτών ή ThisProtector. |
|  [XmlSchemaElement](./xmlschemaelement/)() | Αρχικοποιεί νέα παρουσία της κλάσης [XmlSchemaElement](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Αρχικοποιεί νέα παρουσία της κλάσης [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Αρχικοποιεί νέα παρουσία της κλάσης [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη προς μια παρουσία αυτής της κλάσης. |

## Παρατηρήσεις

Τα αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο μέσω της συνάρτησης [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσιακές αυτής της κλάσης στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για τη μεταβίβαση σε συναρτήσεις ως όρισμα.

## Δείτε επίσης

* Κλάση [XmlSchemaParticle](../xmlschemaparticle/)
* Χώρος ονομάτων [System::Xml::Schema](../)
* Βιβλιοθήκη [Aspose.Slides](../../)