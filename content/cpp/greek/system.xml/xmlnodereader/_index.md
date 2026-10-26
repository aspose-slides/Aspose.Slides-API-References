---
title: XmlNodeReader
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά έναν αναγνώστη που παρέχει γρήγορη, μη αποθηκευμένη πρόσβαση μόνο προς τα εμπρός στα δεδομένα XML σε έναν XmlNode.
type: docs
weight: 365
url: /el/system.xml/xmlnodereader/
---
## XmlNodeReader κλάση

Αντιπροσωπεύει έναν αναγνώστη που παρέχει γρήγορη, μη αποθηκευμένη πρόσβαση μόνο προς τα εμπρός στα δεδομένα XML σε ένα [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [Close](./close/)() override | Αλλάζει το [XmlNodeReader::get_ReadState](./get_readstate/) σε [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) με καθορισμένο URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας το καθορισμένο URI και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας το καθορισμένο URI, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας την καθορισμένη ροή με τις προεπιλεγμένες ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) με την καθορισμένη ροή και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας την καθορισμένη ροή, το βασικό URI και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας την καθορισμένη ροή, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου, τις ρυθμίσεις και το βασικό URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Δημιουργεί μια νέα παρουσία του [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη XML και τις ρυθμίσεις. |
| void [Dispose](../xmlreader/dispose/)() override | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από την τρέχουσα παρουσία της κλάσης [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση διπλής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Επιστρέφει τον αριθμό των γνωρισμάτων στο τρέχον κόμβο. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Επιστρέφει το βασικό URI του τρέχοντος κόμβου. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Επιστρέφει τιμή που υποδεικνύει αν το [XmlNodeReader](./) υλοποιεί τις μεθόδους ανάγνωσης δυαδικού περιεχομένου. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Επιστρέφει τιμή που υποδεικνύει αν το [XmlReader](../xmlreader/) υλοποιεί τη μέθοδο [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Επιστρέφει τιμή που υποδεικνύει αν αυτός ο αναγνώστης μπορεί να αναλύσει και να επιλύσει οντότητες. |
| **int32_t** [get_Depth](./get_depth/)() override | Επιστρέφει το βάθος του τρέχοντος κόμβου στο έγγραφο XML. |
| **bool** [get_EOF](./get_eof/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο αναγνώστης βρίσκεται στο τέλος της ροής. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος έχει γνωρίσματα. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος μπορεί να έχει τιμή [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος είναι γνώρισμα που δημιουργήθηκε από την προεπιλεγμένη τιμή που ορίζεται στο DTD ή στο σχήμα. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος είναι κενό στοιχείο (π.χ. **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Επιστρέφει το τοπικό όνομα του τρέχοντος κόμβου. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Επιστρέφει το URI του ονόματος χώρου (σύμφωνα με τον προδιαγλωττιστή W3C Namespace) του κόμβου στον οποίο βρίσκεται ο αναγνώστης. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Επιστρέφει το [XmlNameTable](../xmlnametable/) που σχετίζεται με αυτήν την υλοποίηση. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Επιστρέφει τον τύπο του τρέχοντος κόμβου. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Επιστρέφει το πρόθεμα του ονόματος χώρου που σχετίζεται με τον τρέχον κόμβο. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Όταν υπερισχύει σε παράγωγη κλάση, επιστρέφει τον χαρακτήρα εισαγωγικού που χρησιμοποιείται για την περιβάλλουσα τιμή ενός γνώρισματος. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Επιστρέφει την κατάσταση του αναγνώστη. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Επιστρέφει τις πληροφορίες σχήματος που έχουν εκχωρηθεί στον τρέχοντα κόμβο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Επιστρέφει το αντικείμενο [XmlReaderSettings](../xmlreadersettings/) που χρησιμοποιείται για τη δημιουργία αυτής της παρουσίασης [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Επιστρέφει την τιμή κειμένου του τρέχοντος κόμβου. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Επιστρέφει τον τύπο για τον τρέχοντα κόμβο. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Επιστρέφει την τρέχουσα περιοχή **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Επιστρέφει την τρέχουσα περιοχή **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Επιστρέφει την τιμή του γνωρίσματος με το καθορισμένο όνομα. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Επιστρέφει την τιμή του γνωρίσματος με το καθορισμένο τοπικό όνομα και το URI του ονόματος χώρου. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Επιστρέφει την τιμή του γνωρίσματος με τον καθορισμένο δείκτη. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Όταν υπερισχύει σε παράγωγη κλάση, παίρνει την τιμή του γνωρίσματος με τον καθορισμένο δείκτη. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Όταν υπερισχύει σε παράγωγη κλάση, παίρνει την τιμή του γνωρίσματος με την καθορισμένη τιμή [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Όταν υπερισχύει σε παράγωγη κλάση, παίρνει την τιμή του γνωρίσματος με τις καθορισμένες τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Επιστρέφει τιμή που υποδεικνύει αν το όρισμα συμβολοσειράς είναι έγκυρο όνομα XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Επιστρέφει τιμή που υποδεικνύει αν το όρισμα συμβολοσειράς είναι έγκυρο token ονόματος XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα έναρξης ή κενό στοιχείο. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα έναρξης ή κενό στοιχείο και αν η τιμή [XmlReader::get_Name](../xmlreader/get_name/) του στοιχείου ταιριάζει με το δοσμένο όρισμα. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα έναρξης ή κενό στοιχείο και αν οι τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) του στοιχείου ταιριάζουν με τις δοσμένες συμβολοσειρές. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση C# lock() κλειδώνοντας. Κλήση άμεσα ή χρήση του αντικειμένου sentinel [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Επίλυση προθέματος ονόματος χώρου στην τρέχουσα εμβέλεια του στοιχείου. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Μεταβαίνει στο γνώρισμα με το καθορισμένο όνομα. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Μεταβαίνει στο γνώρισμα με το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Μεταβαίνει στο γνώρισμα με τον καθορισμένο δείκτη. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Ελέγχει αν ο τρέχων κόμβος είναι κόμβος περιεχομένου (μη κενό κείμενο, **CDATA**, **Element**, **EndElement**, **EntityReference**, ή **EndEntity**). Αν δεν είναι, ο αναγνώστης παρακάμπτει στους επόμενους κόμβους περιεχομένου ή στο τέλος του αρχείου. Παραλείπει κόμβους τύπου: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ή **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Μεταβαίνει στο στοιχείο που περιέχει το τρέχων γνώρισμα. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Μεταβαίνει στο πρώτο γνώρισμα. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Μεταβαίνει στο επόμενο γνώρισμα. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστές ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής σε υποκλάσεις. |
| **bool** [Read](./read/)() override | Διαβάζει τον επόμενο κόμβο από τη ροή. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Αναλύει την τιμή του γνωρίσματος σε έναν ή περισσότερους κόμβους **[Text](../../system.text/)**, **EntityReference**, ή **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Διαβάζει το περιεχόμενο ως αντικείμενο του καθορισμένου τύπου. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά byte αποκωδικοποιημένα από Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το περιεχόμενο και επιστρέφει τα δυαδικά byte αποκωδικοποιημένα από BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως 32-bit ακέραιο με πρόσημο. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως 64-bit ακέραιο με πρόσημο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 32-bit ακέραιο με πρόσημο. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 32-bit ακέραιο με πρόσημο. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 64-bit ακέραιο με πρόσημο. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως 64-bit ακέραιο με πρόσημο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου ταιριάζουν με αυτό του τρέχοντος στοιχείου, έπειτα διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Διαβάζει ένα στοιχείο μόνο κειμένου. Ωστόσο, συνιστάται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) επειδή παρέχει μια πιο απλή προσέγγιση. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Ελέγχει ότι η τιμή [XmlReader::get_Name](../xmlreader/get_name/) του στοιχείου ταιριάζει με τη δοσμένη συμβολοσειρά πριν διαβάσει ένα στοιχείο μόνο κειμένου. Ωστόσο, συνιστάται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) επειδή παρέχει μια πιο απλή προσέγγιση. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι οι τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) του στοιχείου ταιριάζουν με τις δοσμένες συμβολοσειρές πριν διαβάσει ένα στοιχείο μόνο κειμένου. Ωστόσο, συνιστάται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) επειδή παρέχει μια πιο απλή προσέγγιση. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι ετικέτα λήξης και προχωράει τον αναγνώστη στον επόμενο κόμβο. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Όταν υπερισχύει σε παράγωγη κλάση, διαβάζει όλο το περιεχόμενο, συμπεριλαμβανομένων των σημάνσεων, ως συμβολοσειρά. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Όταν υπερισχύει σε παράγωγη κλάση, διαβάζει το περιεχόμενο, συμπεριλαμβανομένων των σημάνσεων, που αντιπροσωπεύει αυτόν τον κόμβο και όλα τα παιδιά του. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Ελέγχει ότι ο τρέχων κόμβος είναι στοιχείο και προχωράει τον αναγνώστη στον επόμενο κόμβο. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι στοιχείο με την δεδομένη τιμή [XmlReader::get_Name](../xmlreader/get_name/) και προχωράει στον επόμενο κόμβο. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι στοιχείο με τις δοσμένες τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) και προχωράει στον επόμενο κόμβο. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Διαβάζει τα περιεχόμενα ενός στοιχείου ή κόμβου κειμένου ως συμβολοσειρά. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Επιστρέφει μια νέα παρουσία [XmlReader](../xmlreader/) που μπορεί να χρησιμοποιηθεί για την ανάγνωση του τρέχοντος κόμβου και όλων των απογόνων του. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο απογόνου στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο απογόνου στοιχείο με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Διαβάζει μέχρι να βρεθεί στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Διαβάζει μέχρι να βρεθεί στοιχείο με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο αδελφό στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο αδελφό στοιχείο με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Διαβάζει μεγάλες ροές κειμένου ενσωματωμένες σε έγγραφο XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τιμές τύπου αναφοράς με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [ResolveEntity](./resolveentity/)() override | Επίλυση της αναφοράς οντότητας για κόμβους **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει τη μετατροπή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Skip](./skip/)() override | Παραλείπει τα παιδιά του τρέχοντος κόμβου. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί τη δήλωση C# lock() ξεκλειδωτής. Κλήση άμεσα ή χρήση του sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Δημιουργεί μια παρουσία της κλάσης [XmlNodeReader](./) χρησιμοποιώντας το καθορισμένο [XmlNode](../xmlnode/). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινόχρηστο δείκτη σε παρουσία αυτής της κλάσης. |

## Παρατηρήσεις

Τα αντικείμενα αυτής της κλάσης θα πρέπει να δημιουργούνται μόνο μέσω της λειτουργίας [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσίες αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή αποτυχίες ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε στις συναρτήσεις ως όρισμα. 

## Δείτε επίσης

* Κλάση [XmlReader](../xmlreader/)
* Κλάση [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)