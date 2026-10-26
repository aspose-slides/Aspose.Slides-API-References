---
title: XmlTextReader
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αντιπροσωπεύει έναν αναγνώστη που παρέχει γρήγορη, μη αποθηκευμένη στην κρυφή μνήμη, πρόσβαση μόνο προς τα εμπρός στα δεδομένα XML.
type: docs
weight: 508
url: /el/system.xml/xmltextreader/
---
## XmlTextReader κλάση

Αντιπροσωπεύει έναν αναγνώστη που παρέχει γρήγορη, μη αποθηκευμένη στην κρυφή μνήμη, πρόσβαση μόνο προς τα εμπρός στα δεδομένα XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Αλλάζει το [XmlReader::get_ReadState](../xmlreader/get_readstate/) σε **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) με το καθορισμένο URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας το καθορισμένο URI και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας το καθορισμένο URI, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για την ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας το καθορισμένο stream με τις προεπιλεγμένες ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) με το καθορισμένο stream και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας το καθορισμένο stream, το βασικό URI και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας το καθορισμένο stream, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για την ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου και τις ρυθμίσεις. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου, τις ρυθμίσεις και το βασικό URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου, τις ρυθμίσεις και τις πληροφορίες περιβάλλοντος για την ανάλυση. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Δημιουργεί ένα νέο αντικείμενο [XmlReader](../xmlreader/) χρησιμοποιώντας τον καθορισμένο αναγνώστη XML και τις ρυθμίσεις. |
| void [Dispose](../xmlreader/dispose/)() override | Αποδεσμεύει όλους τους πόρους που χρησιμοποιούνται από την τρέχουσα παρουσία της κλάσης [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Επιστρέφει τον αριθμό των χαρακτηριστικών στον τρέχοντα κόμβο. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Επιστρέφει το βασικό URI του τρέχοντα κόμβου. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Επιστρέφει τιμή που υποδεικνύει αν το [XmlTextReader](./) υλοποιεί τις μεθόδους ανάγνωσης δυαδικού περιεχομένου. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Επιστρέφει τιμή που υποδεικνύει αν το [XmlTextReader](./) υλοποιεί τη μέθοδο [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Επιστρέφει τιμή που υποδεικνύει αν αυτός ο αναγνώστης μπορεί να αναλύσει και να επιλύσει οντότητες. |
| **int32_t** [get_Depth](./get_depth/)() override | Επιστρέφει το βάθος του τρέχοντα κόμβου στο έγγραφο XML. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Επιστρέφει την απαρίθμηση DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Επιστρέφει την κωδικοποίηση του εγγράφου. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Επιστρέφει τιμή που ορίζει πώς ο αναγνώστης διαχειρίζεται οντότητες. |
| **bool** [get_EOF](./get_eof/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο αναγνώστης βρίσκεται στο τέλος του stream. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος έχει χαρακτηριστικά. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος μπορεί να έχει ένα [XmlTextReader::get_Value](./get_value/) διαφορετικό από το [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος είναι χαρακτηριστικό που δημιουργήθηκε από την προεπιλεγμένη τιμή που ορίζεται στο DTD ή το σχήμα. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Επιστρέφει τιμή που υποδεικνύει αν ο τρέχων κόμβος είναι κενό στοιχείο (π.χ. **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Επιστρέφει τον τρέχοντα αριθμό γραμμής. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Επιστρέφει τη θέση στη γραμμή. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Επιστρέφει το τοπικό όνομα του τρέχοντα κόμβου. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Επιστρέφει το πλήρες όνομα του τρέχοντα κόμβου. |
| **bool** [get_Namespaces](./get_namespaces/)() | Επιστρέφει τιμή που υποδεικνύει αν θα γίνει υποστήριξη χώρου ονομάτων. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Επιστρέφει το URI του χώρου ονομάτων (σύμφωνα με τον ορισμό της W3C Namespace) του κόμβου στον οποίο βρίσκεται ο αναγνώστης. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Επιστρέφει το [XmlNameTable](../xmlnametable/) που σχετίζεται με αυτήν την υλοποίηση. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Επιστρέφει τον τύπο του τρέχοντα κόμβου. |
| **bool** [get_Normalization](./get_normalization/)() | Επιστρέφει τιμή που υποδεικνύει αν θα γίνει κανονικοποίηση λευκών χαρακτήρων και τιμών χαρακτηριστικών. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Επιστρέφει το πρόθεμα του χώρου ονομάτων που σχετίζεται με τον τρέχοντα κόμβο. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Επιστρέφει τιμή που υποδεικνύει αν θα επιτραπεί η επεξεργασία DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Επιστρέφει τον χαρακτήρα εισαγωγικού που χρησιμοποιείται για το περικλείον της τιμής ενός κόμβου χαρακτηριστικού. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Επιστρέφει την κατάσταση του αναγνώστη. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Επιστρέφει τις πληροφορίες σχήματος που έχουν εκχωρηθεί στον τρέχοντα κόμβο ως αποτέλεσμα της επικύρωσης σχήματος. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Επιστρέφει το αντικείμενο [XmlReaderSettings](../xmlreadersettings/) που χρησιμοποιήθηκε για τη δημιουργία αυτής της παρουσίας [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Επιστρέφει την τιμή κειμένου του τρέχοντα κόμβου. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Επιστρέφει τον τύπο του τρέχοντα κόμβου. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Επιστρέφει τιμή που ορίζει πώς διαχειρίζεται τα λευκά διαστήματα. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Επιστρέφει το τρέχον πεδίο ισχύος **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Επιστρέφει το τρέχον πεδίο ισχύος **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο όνομα. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο τοπικό όνομα και URI χώρου ονομάτων. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο ευρετήριο. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογίας της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμένη αναπαράσταση προσαρμοσμένων αντικειμένων. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Επιστρέφει μια συλλογή που περιέχει όλους τους χώρους ονομάτων που είναι επί του παρόντος εντός εμβέλειας. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Επιστρέφει το υπόλοιπο του εσωκλεισμένου XML. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Επιστρέφει τιμή που υποδεικνύει αν η κλάση μπορεί να επιστρέψει πληροφορίες γραμμής. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Όταν παρακαμφθεί σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με το καθορισμένο ευρετήριο. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Όταν παρακαμφθεί σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με την καθορισμένη τιμή [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Όταν παρακαμφθεί σε παράγωγη κλάση, λαμβάνει την τιμή του χαρακτηριστικού με τις καθορισμένες τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# `is`. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Επιστρέφει τιμή που υποδεικνύει αν το όρισμα συμβολοσειράς είναι έγκυρο όνομα XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Επιστρέφει τιμή που υποδεικνύει αν το όρισμα συμβολοσειράς είναι έγκυρο σύμβολο ονόματος XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα έναρξης ή κενό στοιχείο. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα έναρξης ή κενό στοιχείο και αν η τιμή [XmlReader::get_Name](../xmlreader/get_name/) του στοιχείου ταιριάζει με το δοσμένο όρισμα. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Καλεί [XmlReader::MoveToContent](../xmlreader/movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι ετικέτα έναρξης ή κενό στοιχείο και αν οι τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) του στοιχείου ταιριάζουν με τις δοσμένες συμβολοσειρές. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή C# `lock()` για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentinel [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Επίλυση προθέματος χώρου ονομάτων στην εμβέλεια του τρέχοντος στοιχείου. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Μετακινείται στο χαρακτηριστικό με το καθορισμένο όνομα. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Μετακινείται στο χαρακτηριστικό με το καθορισμένο τοπικό όνομα και URI χώρου ονομάτων. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Μετακινείται στο χαρακτηριστικό με το καθορισμένο ευρετήριο. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Ελέγχει αν ο τρέχων κόμβος είναι κόμβος περιεχομένου (μη λευκό κείμενο, **CDATA**, **Element**, **EndElement**, **EntityReference**, ή **EndEntity**). Αν δεν είναι, ο αναγνώστης παραλείπει προς τον επόμενο κόμβο περιεχομένου ή το τέλος του αρχείου. Παραλείπει κόμβους τύπου: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ή **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Μετακινείται στο στοιχείο που περιέχει τον τρέχων κόμβο χαρακτηριστικού. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Μετακινείται στο πρώτο χαρακτηριστικό. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Μετακινείται στο επόμενο χαρακτηριστικό. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| **bool** [Read](./read/)() override | Διαβάζει τον επόμενο κόμβο από το stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους κόμβους **[Text](../../system.text/)**, **EntityReference**, ή **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Αποκωδικοποιεί Base64 και επιστρέφει τα αποκωδικοποιημένα δυαδικά bytes. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Αποκωδικοποιεί **BinHex** και επιστρέφει τα αποκωδικοποιημένα δυαδικά bytes. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Διαβάζει τα κείμενα ενός στοιχείου σε buffer χαρακτήρων. Η μέθοδος έχει σχεδιαστεί για ανάγνωση μεγάλων ροών ενσωματωμένου κειμένου με επαναλαμβανόμενες κλήσεις. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Διαβάζει το περιεχόμενο ως αντικείμενο του καθορισμένου τύπου. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το περιεχόμενο και επιστρέφει τα **Base64** αποκωδικοποιημένα δυαδικά bytes. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το περιεχόμενο και επιστρέφει τα **BinHex** αποκωδικοποιημένα δυαδικά bytes. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως ένα [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως 32-bit ακέραιο με πρόσημο. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως 64-bit ακέραιο με πρόσημο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως ένα [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Διαβάζει το κείμενο στην τρέχουσα θέση ως αντικείμενο [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το περιεχόμενο του στοιχείου ως τον ζητούμενο τύπο. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Διαβάζει το στοιχείο και αποκωδικοποιεί το περιεχόμενο **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αριθμό κινητής υποδιαστολής μονής ακρίβειας. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως 32-bit ακέραιο με πρόσημο. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως 32-bit ακέραιο με πρόσημο. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως 64-bit ακέραιο με πρόσημο. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως 64-bit ακέραιο με πρόσημο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως ένα [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως ένα [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI χώρου ονομάτων ταιριάζουν με το τρέχον στοιχείο, κατόπιν διαβάζει το τρέχων στοιχείο και επιστρέφει το περιεχόμενο ως αντικείμενο [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Διαβάζει στοιχείο μόνο κειμένου. Ωστόσο, συνίσταται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) επειδή παρέχει πιο άμεσο τρόπο χειρισμού. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Ελέγχει ότι η τιμή [XmlReader::get_Name](../xmlreader/get_name/) του βρεθέντος στοιχείου ταιριάζει με τη δοσμένη συμβολοσειρά πριν διαβαστεί στοιχείο μόνο κειμένου. Ωστόσο, συνίσταται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) επειδή παρέχει πιο άμεσο τρόπο χειρισμού. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι οι τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) του βρεθέντος στοιχείου ταιριάζουν με τις δοσμένες συμβολοσειρές πριν διαβαστεί στοιχείο μόνο κειμένου. Ωστόσο, συνίσταται η χρήση της μεθόδου [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) επειδή παρέχει πιο άμεσο τρόπο χειρισμού. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι ετικέτα λήξης και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, διαβάζει όλο το περιεχόμενο, συμπεριλαμβανομένου του markup, ως συμβολοσειρά. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, διαβάζει το περιεχόμενο, συμπεριλαμβανομένου του markup, που αντιπροσωπεύει αυτόν τον κόμβο και όλα τα παιδιά του. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Ελέγχει ότι ο τρέχων κόμβος είναι στοιχείο και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι στοιχείο με την δοσμένη τιμή [XmlReader::get_Name](../xmlreader/get_name/) και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι στοιχείο με τις δοσμένες τιμές [XmlReader::get_LocalName](../xmlreader/get_localname/) και [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) και προχωρά τον αναγνώστη στον επόμενο κόμβο. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Διαβάζει το περιεχόμενο ενός στοιχείου ή ενός κόμβου κειμένου ως συμβολοσειρά. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Επιστρέφει μια νέα παρουσία [XmlReader](../xmlreader/) που μπορεί να χρησιμοποιηθεί για ανάγνωση του τρέχοντα κόμβου και όλων των απογόνων του. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο απογόμενο στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο απογόμενο στοιχείο με το καθορισμένο τοπικό όνομα και URI χώρου ονομάτων. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Διαβάζει μέχρι να βρεθεί στοιχείο με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Διαβάζει μέχρι να βρεθεί στοιχείο με το καθορισμένο τοπικό όνομα και URI χώρου ονομάτων. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο στοιχείο αδερφικό με το καθορισμένο πλήρες όνομα. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Προχωρά το [XmlReader](../xmlreader/) στο επόμενο αδερφικό στοιχείο με το καθορισμένο τοπικό όνομα και URI χώρου ονομάτων. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Διαβάζει μεγάλες ροές κειμένου ενσωματωμένου σε έγγραφο XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τιμή τύπου με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική μορφή του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική μορφή του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [ResetState](./resetstate/)() | Επαναφέρει την κατάσταση του αναγνώστη στην [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Επίλυση της αναφοράς οντότητας για κόμβους **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Ορίζει την απαρίθμηση DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Ορίζει τιμή που καθορίζει πώς ο αναγνώστης διαχειρίζεται οντότητες. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ορίζει τιμή που υποδεικνύει αν θα γίνει υποστήριξη χώρου ονομάτων. |
| void [set_Normalization](./set_normalization/)(**bool**) | Ορίζει τιμή που υποδεικνύει αν θα κανονικοποιηθούν τα λευκά διαστήματα και οι τιμές χαρακτηριστικών. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Ορίζει τιμή που υποδεικνύει αν θα επιτραπεί η επεξεργασία DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Ορίζει τιμή που καθορίζει πώς διαχειρίζονται τα λευκά διαστήματα. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Ορίζει το [XmlResolver](../xmlresolver/) που χρησιμοποιείται για την επίλυση αναφορών DTD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινή). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Skip](./skip/)() override | Παραλείπει τα παιδιά του τρέχοντα κόμβου. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# `lock()` για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθεσια· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο stream. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο URL και stream. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο stream και [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο URL, stream και [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο URL και TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο TextReader και [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο URL, TextReader και [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο stream, XmlNodeType και [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με τη συγκεκριμένη συμβολοσειρά, XmlNodeType και [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο αρχείο. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlTextReader](./) με το καθορισμένο αρχείο και [XmlNameTable](../xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Ορισμοί τύπου

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη σε παρουσία αυτής της κλάσης. |

## Παρατηρήσεις

Συνιστάται η χρήση της κλάσης [XmlReader](../xmlreader/) αντί αυτού.

Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παραδείγματα αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή `operator new`, διότι μπορεί να οδηγήσει σε σφάλματα χρόνου εκτέλεσης ή/και σε σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα.

## Δείτε επίσης

* Κλάση [XmlReader](../xmlreader/)
* Κλάση [IXmlLineInfo](../ixmllineinfo/)
* Κλάση [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)