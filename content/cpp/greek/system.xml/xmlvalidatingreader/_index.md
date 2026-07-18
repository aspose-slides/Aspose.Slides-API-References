---
title: XmlValidatingReader
second_title: Αναφορά API του Aspose.Slides για C++
description: Αντιπροσωπεύει έναν αναγνώστη που παρέχει επικύρωση ορισμού τύπου εγγράφου (DTD), σχήματος XML-Data Reduced (XDR) και γλώσσας ορισμού σχήματος XML (XSD).
type: docs
weight: 547
url: /el/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader κλάση

Αντιπροσωπεύει έναν αναγνώστη που παρέχει επικύρωση ορισμού τύπου εγγράφου (DTD), σχήματος XML-Data Reduced (XDR) και γλώσσας ορισμού XML [Schema](../../system.xml.schema/) (XSD).

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [Close](./close/)() override | Αλλάζει το [XmlReader::get_ReadState](../xmlreader/get_readstate/) σε Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance με το καθορισμένο URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο URI και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο URI, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο ρεύμα με προεπιλεγμένες ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance με το καθορισμένο ρεύμα και ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο ρεύμα, το βασικό URI και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο ρεύμα, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο text reader. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο text reader και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο text reader, τις ρυθμίσεις και το βασικό URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας το καθορισμένο text reader, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Δημιουργεί ένα νέο [XmlReader](../xmlreader/) instance χρησιμοποιώντας τον καθορισμένο XML reader και τις ρυθμίσεις. |
| void [Dispose](../xmlreader/dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί η τρέχουσα εμφάνιση της κλάσης [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη λογική του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Επιστρέφει τον αριθμό των ιδιοτήτων (attributes) στον τρέχον κόμβο. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Επιστρέφει το base URI του τρέχοντος κόμβου. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Επιστρέφει τιμή που υποδεικνύει εάν το [XmlValidatingReader](./) υλοποιεί τις μεθόδους ανάγνωσης δυαδικού περιεχομένου. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Επιστρέφει τιμή που υποδεικνύει εάν το [XmlReader](../xmlreader/) υλοποιεί τη μέθοδο [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Επιστρέφει τιμή που υποδεικνύει εάν αυτός ο αναγνώστης μπορεί να αναλύσει και να επιλύσει οντότητες. |
| **int32_t** [get_Depth](./get_depth/)() override | Επιστρέφει το βάθος του τρέχοντος κόμβου στο έγγραφο XML. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Επιστρέφει το χαρακτηριστικό κωδικοποίησης για το έγγραφο. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Επιστρέφει τιμή που καθορίζει πώς ο αναγνώστης διαχειρίζεται τις οντότητες. |
| **bool** [get_EOF](./get_eof/)() override | Επιστρέφει τιμή που υποδεικνύει εάν ο αναγνώστης βρίσκεται στην τελική θέση του ρεύματος. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Επιστρέφει τιμή που υποδεικνύει εάν ο τρέχων κόμβος έχει ιδιότητες. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Επιστρέφει τιμή που υποδεικνύει εάν ο τρέχων κόμβος μπορεί να έχει ένα [XmlValidatingReader::get_Value](./get_value/) διαφορετικό από [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Επιστρέφει τιμή που υποδεικνύει εάν ο τρέχων κόμβος είναι ιδιότητα που δημιουργήθηκε από την προεπιλεγμένη τιμή που ορίζεται στον ορισμό τύπου εγγράφου (DTD) ή στο σχήμα. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Επιστρέφει τιμή που υποδεικνύει εάν ο τρέχων κόμβος είναι κενό στοιχείο (π.χ., **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Επιστρέφει τον τρέχον αριθμό γραμμής. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Επιστρέφει τη θέση στη γραμμή. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Επιστρέφει το τοπικό όνομα του τρέχοντος κόμβου. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου. |
| **bool** [get_Namespaces](./get_namespaces/)() | Επιστρέφει τιμή που υποδεικνύει εάν θα γίνει υποστήριξη χώρου ονομάτων. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Επιστρέφει το Uniform Resource Identifier (URI) του namespace (όπως ορίζεται από το World Wide [Web](../../system.web/) Consortium (W3C) Namespace specification) του κόμβου στον οποίο βρίσκεται ο αναγνώστης. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Επιστρέφει το [XmlNameTable](../xmlnametable/) που σχετίζεται με αυτήν την υλοποίηση. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Επιστρέφει τον τύπο του τρέχοντος κόμβου. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Επιστρέφει το πρόθεμα namespace που σχετίζεται με τον τρέχοντα κόμβο. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Επιστρέφει τον χαρακτήρα εισαγωγικού που χρησιμοποιείται για να περικλείει την τιμή ενός κόμβου ιδιότητας. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Επιστρέφει το [XmlReader](../xmlreader/) που χρησιμοποιείται για τη δημιουργία αυτού του [XmlValidatingReader](./). |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Επιστρέφει την κατάσταση του αναγνώστη. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Επιστρέφει τις πληροφορίες σχήματος που έχουν εκχωρηθεί στον τρέχοντα κόμβο ως αποτέλεσμα επικύρωσης σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Επιστρέφει ένα XmlSchemaCollection για χρήση στην επικύρωση. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Επιστρέφει ένα αντικείμενο τύπου σχήματος. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Επιστρέφει το αντικείμενο [XmlReaderSettings](../xmlreadersettings/) που χρησιμοποιήθηκε για τη δημιουργία αυτής της εμφάνισης [XmlReader](../xmlreader/). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Επιστρέφει τιμή που υποδεικνύει τον τύπο επικύρωσης που θα εκτελεστεί. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Επιστρέφει την τιμή κειμένου του τρέχοντος κόμβου. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Επιστρέφει τον τύπο για τον τρέχοντα κόμβο. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Επιστρέφει την τρέχουσα εμβέλεια **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Επιστρέφει την τρέχουσα εμβέλεια **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Επιστρέφει την τιμή της ιδιότητας με το καθορισμένο όνομα. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Επιστρέφει την τιμή της ιδιότητας με το καθορισμένο τοπικό όνομα και το Uniform Resource Identifier (URI) του namespace. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Επιστρέφει την τιμή της ιδιότητας με το καθορισμένο δείκτη. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Επιστρέφει τιμή που υποδεικνύει εάν η κλάση μπορεί να επιστρέψει πληροφορίες γραμμής. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Όταν παρακαμφθεί σε παραγόμενη κλάση, λαμβάνει την τιμή της ιδιότητας με το καθορισμένο δείκτη. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Όταν παρακαμφθεί σε παραγόμενη κλάση, λαμβάνει την τιμή της ιδιότητας με τη συγκεκριμένη τιμή [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Όταν παρακαμφθεί σε παραγόμενη κλάση, λαμβάνει την τιμή της ιδιότητας με τις συγκεκριμένες τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιστοιχεί σε μια εμφάνιση τύπου όπως ορίζεται από το targetType. Αντίστοιχο του τελεστή C# `is`. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Επιστρέφει τιμή που υποδεικνύει εάν το όρισμα κειμένου είναι έγκυρο όνομα XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Επιστρέφει τιμή που υποδεικνύει εάν το όρισμα κειμένου είναι έγκυρο token ονόματος XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα εκκίνησης ή κενό στοιχείο. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα εκκίνησης ή κενό στοιχείο και αν η τιμή [XmlReader::get_Name](../xmlreader/get_name/) του ευρεθέντος στοιχείου ταιριάζει με το δοθέν όρισμα. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα εκκίνησης ή κενό στοιχείο και αν οι τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) του ευρεθέντος στοιχείου ταιριάζουν με τις δοθείσες συμβολοσειρές. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement κλειδώματος C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Επιλύει ένα πρόθεμα namespace στην εμβέλεια του τρέχοντος στοιχείου. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Μετακινείται στην ιδιότητα με το καθορισμένο όνομα. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Μετακινείται στην ιδιότητα με το καθορισμένο τοπικό όνομα και το Uniform Resource Identifier (URI) του namespace. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Μετακινείται στην ιδιότητα με το καθορισμένο δείκτη. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Ελέγχει εάν ο τρέχων κόμβος είναι κόμβος περιεχομένου (μη λευκό κείμενο, **CDATA**, **Element**, **EndElement**, **EntityReference**, ή **EndEntity**). Αν δεν είναι, ο αναγνώστης παραλείπει μέχρι τον επόμενο κόμβο περιεχομένου ή το τέλος του αρχείου. Παραλείπει κόμβους τύπου: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ή **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Μετακινείται στο στοιχείο που περιέχει τον τρέχοντα κόμβο ιδιότητας. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Μετακινείται στην πρώτη ιδιότητα. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Μετακινείται στην επόμενη ιδιότητα. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλάσεων-προσφυγών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλάσεων-προσφυγών. |
| **bool** [Read](./read/)() override | Διαβάζει τον επόμενο κόμβο από το ρεύμα. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Αναλύει την τιμή της ιδιότητας σε έναν ή περισσότερους κόμβους **[Text](../../system.text/)**, **EntityReference**, ή **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Διαβάζει το περιεχόμενο ως αντικείμενο του καθορισμένου τύπου. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά bytes που αποκωδικοποιήθηκαν από Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά bytes που αποκωδικοποιήθηκαν από BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως αντικείμενο [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως 32-bit υπογεγραμμένο ακέραιο. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως 64-bit υπογεγραμμένο ακέραιο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Διαβάζει το κειμενικό περιεχόμενο στη τρέχουσα θέση ως αντικείμενο [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 32-bit υπογεγραμμένο ακέραιο. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 32-bit υπογεγραμμένο ακέραιο. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 64-bit υπογεγραμμένο ακέραιο. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 64-bit υπογεγραμμένο ακέραιο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI namespace ταιριάζουν με αυτά του τρέχοντος στοιχείου, στη συνέχεια διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Διαβάζει ένα στοιχείο μόνο κειμένου. Ωστόσο, συνιστάται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) καθώς παρέχει πιο άμεσο τρόπο διαχείρισης. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Ελέγχει ότι η τιμή [XmlReader::get_Name](../xmlreader/get_name/) του ευρεθέντος στοιχείου ταιριάζει με τη δοθείσα συμβολοσειρά πριν διαβάσει ένα στοιχείο μόνο κειμένου. Ωστόσο, συνιστάται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) καθώς παρέχει πιο άμεσο τρόπο διαχείρισης. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι οι τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) του ευρεθέντος στοιχείου ταιριάζουν με τις δοθείσες συμβολοσειρές πριν διαβάσει ένα στοιχείο μόνο κειμένου. Ωστόσο, συνιστάται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) καθώς παρέχει πιο άμεσο τρόπο διαχείρισης. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι ετικέτα λήξης και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Όταν παρακαμφθεί σε παραγόμενη κλάση, διαβάζει όλο το περιεχόμενο, συμπεριλαμβανομένου του markup, ως συμβολοσειρά. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Όταν παρακαμφθεί σε παραγόμενη κλάση, διαβάζει το περιεχόμενο, συμπεριλαμβανομένου του markup, που αντιπροσωπεύει αυτόν τον κόμβο και όλα τα παιδιά του. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Ελέγχει ότι ο τρέχων κόμβος είναι στοιχείο και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι στοιχείο με την δοθείσα τιμή [XmlReader::get_Name](../xmlreader/get_name/) και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι στοιχείο με τις δοθείσες τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Διαβάζει το περιεχόμενο ενός στοιχείου ή ενός κόμβου κειμένου ως συμβολοσειρά. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Επιστρέφει μια νέα εμφάνιση [XmlReader](../xmlreader/) που μπορεί να χρησιμοποιηθεί για την ανάγνωση του τρέχοντος κόμβου και όλων των απογόνων του. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο απογόνου στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο απογόνου στοιχείο με το καθορισμένο τοπικό όνομα και το URI namespace. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Διαβάζει μέχρι να βρεθεί στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Διαβάζει μέχρι να βρεθεί στοιχείο με το καθορισμένο τοπικό όνομα και το URI namespace. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο αδερφό στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο αδερφό στοιχείο με το καθορισμένο τοπικό όνομα και το URI namespace. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Επιστρέφει τον τύπο χρόνου εκτέλεσης για τον καθορισμένο τύπο γλώσσας XML [Schema](../../system.xml.schema/) (XSD). |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Διαβάζει μεγάλα τμήματα κειμένου ενσωματωμένα σε έγγραφο XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τιμή τύπου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [ResolveEntity](./resolveentity/)() override | Επιλύει την αναφορά οντότητας για κόμβους **EntityReference**. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Ορίζει τιμή που καθορίζει πώς ο αναγνώστης διαχειρίζεται τις οντότητες. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ορίζει τιμή που υποδεικνύει εάν θα γίνει υποστήριξη namespace. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Ορίζει τιμή που υποδεικνύει τον τύπο επικύρωσης που θα εκτελεστεί. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Ορίζει το [XmlResolver](../xmlresolver/) που χρησιμοποιείται για την επίλυση εξωτερικών ορισμών τύπου εγγράφου (DTD) και αναφορών θέσεων σχήματος. Το [XmlResolver](../xmlresolver/) χρησιμοποιείται επίσης για τη διαχείριση εισαγωγών ή περιλαμβανομένων στοιχείων στα σχήματα XML [Schema](../../system.xml.schema/) (XSD). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη κατάσταση. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνες αναφορές ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνες αναφορές ή ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | Παράλειψη των παιδιών του τρέχοντος κόμβου. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δήλωση C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Προσθέτει έναν χειριστή συμβάντος για λήψη πληροφοριών σχετικά με σφάλματα επικύρωσης DTD, XDR ή [Schema](../../system.xml.schema/) σχήματος XML (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Αφαιρεί έναν χειριστή συμβάντος για λήψη πληροφοριών σχετικά με σφάλματα επικύρωσης DTD, XDR ή [Schema](../../system.xml.schema/) σχήματος XML (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνες αναφορές ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνες αναφορές ή ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [XmlValidatingReader](./) που επικυρώνει το περιεχόμενο που επιστρέφεται από το δεδομένο [XmlReader](../xmlreader/). |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [XmlValidatingReader](./) με τις καθορισμένες τιμές. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [XmlValidatingReader](./) με τις καθορισμένες τιμές. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τύποι ορισμού

| Typedef | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη σε μια εμφάνιση αυτής της κλάσης. |

## Παρατηρήσεις

Παρωχημένο
:   Αυτή η κλάση είναι παρωχημένη. Συνιστάται η χρήση της κλάσης [XmlReaderSettings](../xmlreadersettings/) και της μεθόδου [XmlReader::Create](../xmlreader/create/) για τη δημιουργία ενός επικυρωμένου αναγνώστη XML.

Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο με τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε εμφανίσεις αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε έναν δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα.

## Δείτε επίσης

* Κλάση [XmlReader](../xmlreader/)
* Κλάση [IXmlLineInfo](../ixmllineinfo/)
* Κλάση [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)