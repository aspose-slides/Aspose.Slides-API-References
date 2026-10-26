---
title: XmlSchema
second_title: Αναφορά API Aspose.Slides για C++
description: Μια αναπαράσταση μνήμης ενός XML Schema, όπως καθορίζεται από το Παγκόσμιο Συμβούλιο Ιστού (W3C) και .
type: docs
weight: 79
url: /el/system.xml.schema/xmlschema/
---
## XmlSchema κλάση

Μια αναπαράσταση μνήμης ενός XML [Schema](../), όπως καθορίζεται από το Παγκόσμιο [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) και [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Methods

| Method | Description |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | Συγκενώνει το XML [Schema](../)[Object](../../system/object/) Model (SOM) σε πληροφορίες σχήματος για επικύρωση. Χρησιμοποιείται για τον έλεγχο της συντακτικής και σημασιολογικής δομής του προγραμματιστικά δημιουργημένου SOM. Ο έλεγχος σημασιολογικής επικύρωσης πραγματοποιείται κατά τη διάρκεια της μεταγλώττισης. |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Συγκενώνει το XML [Schema](../)[Object](../../system/object/) Model (SOM) σε πληροφορίες σχήματος για επικύρωση. Χρησιμοποιείται για τον έλεγχο της συντακτικής και σημασιολογικής δομής του προγραμματιστικά δημιουργημένου SOM. Ο έλεγχος σημασιολογικής επικύρωσης πραγματοποιείται κατά τη διάρκεια της μεταγλώττισης. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if\<![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμα και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμα και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | Επιστρέφει τη μορφή για τα χαρακτηριστικά που δηλώνονται στον προορισμό χώρου ονομάτων του σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση σχήματος όλων των παγκόσμιων ομάδων χαρακτηριστικών στο σχήμα. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση σχήματος για όλα τα χαρακτηριστικά στο σχήμα. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | Επιστρέφει το χαρακτηριστικό **blockDefault** που ορίζει την προεπιλεγμένη τιμή του χαρακτηριστικού **block** σε στοιχεία και σύνθετους τύπους στο **targetNamespace** του σχήματος. |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | Επιστρέφει τη μορφή για τα στοιχεία που δηλώνονται στον προορισμό χώρου ονομάτων του σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση σχήματος για όλα τα στοιχεία στο σχήμα. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | Επιστρέφει το χαρακτηριστικό **finalDefault** που ορίζει την προεπιλεγμένη τιμή του χαρακτηριστικού **final** σε στοιχεία και σύνθετους τύπους στον προορισμό χώρου ονομάτων του σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση σχήματος όλων των ομάδων στο σχήμα. |
| [String](../../system/string/) [get_Id](./get_id/)() | Επιστρέφει το αναγνωριστικό συμβολοσειράς. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | Επιστρέφει τη συλλογή των περιλαμβανόμενων και εισαγόμενων σχημάτων. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Δεικνύει εάν το σχήμα έχει μεταγλωττιστεί. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | Επιστρέφει τη συλλογή των στοιχείων σχήματος στο σχήμα και χρησιμοποιείται για την προσθήκη νέων τύπων στοιχείων στο επίπεδο στοιχείου **schema**. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Επιστρέφει τον αριθμό γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Επιστρέφει τη θέση γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Επιστρέφει τα XmlSerializerNamespaces για χρήση με αυτό το αντικείμενο σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση σχήματος για όλες τις σημειώσεις στο σχήμα. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Επιστρέφει τον γονέα αυτού του [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | Επιστρέφει την τιμή μετά τη μεταγλώττιση σχήματος όλων των τύπων σχήματος στο σχήμα. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Επιστρέφει τη θέση προέλευσης για το αρχείο που φόρτωσε το σχήμα. |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | Επιστρέφει το Uniform Resource Identifier (URI) του προορισμού χώρου ονομάτων του σχήματος. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | Επιστρέφει τα προσδιορισμένα χαρακτηριστικά που δεν ανήκουν στον προορισμό χώρου ονομάτων του σχήματος. |
| [String](../../system/string/) [get_Version](./get_version/)() | Επιστρέφει την έκδοση του σχήματος. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγορίων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεσ/operator ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγορίων. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Αναγνάζει ένα XML [Schema](../) από το παρεχόμενο [IO::TextReader](../../system.io/textreader/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Αναγνάζει ένα XML [Schema](../) από το παρεχόμενο ρεύμα. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Αναγνάζει ένα XML [Schema](../) από το παρεχόμενο [XmlReader](../../system.xml/xmlreader/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Ορίζει τη μορφή για τα χαρακτηριστικά που δηλώνονται στον προορισμό χώρου ονομάτων του σχήματος. |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Ορίζει το χαρακτηριστικό **blockDefault** που ορίζει την προεπιλεγμένη τιμή του χαρακτηριστικού **block** σε στοιχεία και σύνθετους τύπους στο **targetNamespace** του σχήματος. |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Ορίζει τη μορφή για τα στοιχεία που δηλώνονται στον προορισμό χώρου ονομάτων του σχήματος. |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Ορίζει το χαρακτηριστικό **finalDefault** που ορίζει την προεπιλεγμένη τιμή του χαρακτηριστικού **final** σε στοιχεία και σύνθετους τύπους στον προορισμό χώρου ονομάτων του σχήματος. |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | Ορίζει το αναγνωριστικό συμβολοσειράς. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Ορίζει τον αριθμό γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Ορίζει τη θέση γραμμής στο αρχείο στον οποίο αναφέρεται το στοιχείο **schema**. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Ορίζει τα XmlSerializerNamespaces για χρήση με αυτό το αντικείμενο σχήματος. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Ορίζει τον γονέα αυτού του [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Ορίζει τη θέση προέλευσης για το αρχείο που φόρτωσε το σχήμα. |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | Ορίζει το Uniform Resource Identifier (URI) του προορισμού χώρου ονομάτων του σχήματος. |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Ορίζει τα προσδιορισμένα χαρακτηριστικά που δεν ανήκουν στον προορισμό χώρου ονομάτων του σχήματος. |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | Ορίζει την έκδοση του σχήματος. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Γράφει το XML [Schema](../) στο παρεχόμενο ρεύμα δεδομένων. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Γράφει το XML [Schema](../) στο παρεχόμενο Stream χρησιμοποιώντας το [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) που ορίζεται. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Γράφει το XML [Schema](../) στο παρεχόμενο [IO::TextWriter](../../system.io/textwriter/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Γράφει το XML [Schema](../) στο παρεχόμενο TextWriter. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Γράφει το XML [Schema](../) στο παρεχόμενο [XmlWriter](../../system.xml/xmlwriter/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Γράφει το XML [Schema](../) στο παρεχόμενο [XmlWriter](../../system.xml/xmlwriter/). |
| [XmlSchema](./xmlschema/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlSchema](./). |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Fields

| Field | Description |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | Το χώρο ονομάτων της υπόδειξης σχήματος XML. Αυτό το πεδίο είναι σταθερό. |
| static [Namespace](./namespace/) | Το χώρο ονομάτων του σχήματος XML. Αυτό το πεδίο είναι σταθερό. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη σε μια υπόδειξη αυτής της κλάσης. |

## Παρατηρήσεις

Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμές αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ισχυρισμού. Πάντοτε κυλίστε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα. 

## Δείτε επίσης

* Κλάση [XmlSchemaObject](../xmlschemaobject/)
* Χώρος ονομάτων [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)