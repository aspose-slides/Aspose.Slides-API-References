---
title: XmlCharacterData
second_title: Αναφορά API του Aspose.Slides για C++
description: Παρέχει μεθόδους διαχείρισης κειμένου που χρησιμοποιούνται από πολλές κλάσεις.
type: docs
weight: 118
url: /el/system.xml/xmlcharacterdata/
---
## XmlCharacterData class

Παρέχει μεθόδους διαχείρισης κειμένου που χρησιμοποιούνται από πολλές κλάσεις.

```cpp
class XmlCharacterData : public System::Xml::XmlLinkedNode
```

## Methods

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Προσθέτει τον καθορισμένο κόμβο στο τέλος της λίστας των θυγατρικών κόμβων, αυτού του κόμβου. |
| virtual void [AppendData](./appenddata/)([String](../../system/string/)) | Προσθέτει το καθορισμένο συμβολοσειρά στο τέλος των δεδομένων χαρακτήρων του κόμβου. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Λαμβάνει επαναλήπτη που δείχνει στο πρώτο στοιχείο (εάν υπάρχει) της συλλογής. Αυτός ο επαναλήπτης δεν μπορεί να χρησιμοποιηθεί για την αλλαγή του αναφερόμενου αντικειμένου επειδή [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) επιστρέφει ένα αντίγραφο-αντικείμενο του T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Λαμβάνει επαναλήπτη που δείχνει στο πρώτο στοιχείο (εάν υπάρχει) της σταθερά-πολιτικής εκδοχής της συλλογής. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Λαμβάνει επαναλήπτη που δείχνει στο πρώτο σταθερά-πολιτικό στοιχείο (εάν υπάρχει) της συλλογής. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Λαμβάνει επαναλήπτη που δείχνει αμέσως μετά το τελευταίο σταθερά-πολιτικό στοιχείο (εάν υπάρχει) της συλλογής. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Δημιουργεί ένα αντίγραφο αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](../xmlnode/clonenode/)(**bool**) | Δημιουργεί ένα αντίγραφο του κόμβου, όταν υπερκαλύπτεται σε παράγωγη κλάση. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Δημιουργεί ένα XPathNavigator για την πλοήγηση αυτού του αντικειμένου. |
| virtual void [DeleteData](./deletedata/)(**int32_t**, **int32_t**) | Αφαιρεί μια περιοχή χαρακτήρων από τον κόμβο. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Λαμβάνει επαναλήπτη που δείχνει αμέσως μετά το τελευταίο στοιχείο (εάν υπάρχει) της συλλογής. Αυτός ο επαναλήπτης δεν μπορεί να χρησιμοποιηθεί για την αλλαγή του αναφερόμενου αντικειμένου επειδή [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) επιστρέφει ένα αντίγραφο-αντικείμενο του T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Λαμβάνει επαναλήπτη που δείχνει αμέσως μετά το τελευταίο στοιχείο (εάν υπάρχει) της σταθερά-πολιτικής εκδοχής της συλλογής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Επιστρέφει ένα [XmlAttributeCollection](../xmlattributecollection/) που περιέχει τα χαρακτηριστικά αυτού του κόμβου. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Επιστρέφει το βασικό URI του τρέχοντος κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Επιστρέφει όλους τους θυγατρικούς κόμβους του κόμβου. |
| virtual [String](../../system/string/) [get_Data](./get_data/)() | Επιστρέφει τα δεδομένα του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Επιστρέφει το πρώτο παιδί του κόμβου. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτός ο κόμβος έχει οποιουσδήποτε θυγατρικούς κόμβους. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | Επιστρέφει τις συναρμολογημένες τιμές του κόμβου και όλων των παιδιών του κόμβου. |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | Επιστρέφει το σήμανση που αντιπροσωπεύει μόνο τους θυγατρικούς κόμβους αυτού του κόμβου. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν ο κόμβος είναι μόνο για ανάγνωση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Επιστρέφει το τελευταίο παιδί του κόμβου. |
| virtual **int32_t** [get_Length](./get_length/)() | Επιστρέφει το μήκος των δεδομένων, σε χαρακτήρες. |
| virtual [String](../../system/string/) [get_LocalName](../xmlnode/get_localname/)() | Επιστρέφει το τοπικό όνομα του κόμβου, όταν υπερκαλύπτεται σε παράγωγη κλάση. |
| virtual [String](../../system/string/) [get_Name](../xmlnode/get_name/)() | Επιστρέφει το πλήρες όνομα του κόμβου, όταν υπερκαλύπτεται σε παράγωγη κλάση. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Επιστρέφει το URI του χώρου ονομάτων αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Επιστρέφει τον κόμβο που ακολουθεί αμέσως αυτόν τον κόμβο. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](../xmlnode/get_nodetype/)() | Επιστρέφει τον τύπο του τρέχοντος κόμβου, όταν υπερκαλύπτεται σε παράγωγη κλάση. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Επιστρέφει το σήμανση που περιέχει αυτόν τον κόμβο και όλους τους θυγατρικούς του κόμβους. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Επιστρέφει το [XmlDocument](../xmldocument/) στο οποίο ανήκει αυτός ο κόμβος. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Επιστρέφει το γονέα αυτού του κόμβου (για κόμβους που μπορούν να έχουν γονείς). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Επιστρέφει το πρόθεμα του χώρου ονομάτων αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Επιστρέφει τον κόμβο που προηγείται αμέσως αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Επιστρέφει τον κόμβο κειμένου που προηγείται αμέσως αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Επιστρέφει το σύνολο πληροφοριών μετά τη διασυζήτηση σχήματος που έχει ανατεθεί σε αυτόν τον κόμβο ως αποτέλεσμα της επικύρωσης σχήματος. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Επιστρέφει την τιμή του κόμβου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Επιστρέφει έναν ενομετρητή που επαναλαμβάνει τους θυγατρικούς κόμβους στον τρέχοντα κόμβο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την καταμετρητική (hash) προσαρμοσμένων αντικειμένων. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Αναζητά τη πιο κοντινή δήλωση **xmlns** για το δεδομένο πρόθεμα που είναι εντός εμβέλειας του τρέχοντος κόμβου και επιστρέφει το URI του χώρου ονομάτων στη δήλωση. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Αναζητά τη πιο κοντινή δήλωση **xmlns** για το δεδομένο URI χώρου ονομάτων που είναι εντός εμβέλειας του τρέχοντος κόμβου και επιστρέφει το πρόθεμα που ορίζεται σε αυτή τη δήλωση. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Επιστρέφει το πρώτο παιδικό στοιχείο με το καθορισμένο [XmlNode::get_Name](../xmlnode/get_name/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Επιστρέφει το πρώτο παιδικό στοιχείο με τις καθορισμένες τιμές [XmlNode::get_LocalName](../xmlnode/get_localname/) και [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Εισάγει τον καθορισμένο κόμβο αμέσως μετά τον καθορισμένο κόμβο-αναφορά. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Εισάγει τον καθορισμένο κόμβο αμέσως πριν τον καθορισμένο κόμβο-αναφορά. |
| virtual void [InsertData](./insertdata/)(**int32_t**, [String](../../system/string/)) | Εισάγει τη καθορισμένη συμβολοσειρά στη καθορισμένη θέση χαρακτήρα. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# «is». |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει μια συνάρτηση συγκεντρωτή σε μια ακολουθία. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει εάν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Καθορίζει εάν μια ακολουθία περιέχει στοιχεία. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει εάν υπάρχει κάποιο στοιχείο στην ακολουθία ή εάν ικανοποιεί τη συνθήκη. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Συνενώνει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Καθορίζει εάν μια ακολουθία περιέχει την καθορισμένη τιμή. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενος με άμεση καταμέτρηση). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν τη συγκεκριμένη συνθήκη. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο στη συγκεκριμένη θέση στην ακολουθία. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο στη συγκεκριμένη θέση στην ακολουθία. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί τη συγκεκριμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή εάν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει την ελάχιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Αντιστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Μετασχηματίζει τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Προβάλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Επιστρέφει συγκεκριμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου λογικού τύπου. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το C# lock() statement κλειδώνοντας. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| virtual void [Normalize](../xmlnode/normalize/)() | Τοποθετεί όλους τους [XmlText](../xmltext/) κόμβους σε πλήρη βάθος του υποδένδρο κάτω από αυτό το [XmlNode](../xmlnode/) σε «κανονική» μορφή όπου μόνο το σήμανση (δηλαδή ετικέτες, σχόλια, οδηγίες επεξεργασίας, ενότητες CDATA και παραπομπές οντοτήτων) διαχωρίζει τους κόμβους [XmlText](../xmltext/), δηλαδή δεν υπάρχουν προσεκτικοί κόμβοι [XmlText](../xmltext/). |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευή αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Προσθέτει τον καθορισμένο κόμβο στην αρχή της λίστας των θυγατρικών κόμβων για αυτόν τον κόμβο. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τύπου τιμής με nullptr με αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Αφαιρεί όλους τους θυγατρικούς κόμβους και/ή τα χαρακτηριστικά του τρέχοντος κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Αφαιρεί τον καθορισμένο θυγατρικό κόμβο. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Αντικαθιστά τον θυγατρικό κόμβο **oldChild** με τον κόμβο **newChild**. |
| virtual void [ReplaceData](./replacedata/)(**int32_t**, **int32_t**, [String](../../system/string/)) | Αντικαθιστά τον καθορισμένο αριθμό χαρακτήρων ξεκινώντας από τη θέση με τη καθορισμένη συμβολοσειρά. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Επιλέγει μια λίστα κόμβων που ταιριάζουν με την έκφραση [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Επιλέγει μια λίστα κόμβων που ταιριάζουν με την έκφραση [XPath](../../system.xml.xpath/). Όλα τα πρόθεμα που βρέθηκαν στην έκφραση [XPath](../../system.xml.xpath/) επιλύονται με το παρεχόμενο [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Επιλέγει το πρώτο [XmlNode](../xmlnode/) που ταιριάζει με την έκφραση [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Επιλέγει το πρώτο [XmlNode](../xmlnode/) που ταιριάζει με την έκφραση [XPath](../../system.xml.xpath/). Όλα τα πρόθεμα που βρέθηκαν στην έκφραση [XPath](../../system.xml.xpath/) επιλύονται με το παρεχόμενο [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual void [set_Data](./set_data/)([String](../../system/string/)) | Ορίζει τα δεδομένα του κόμβου. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Ορίζει τις συναρμολογημένες τιμές του κόμβου και όλων των παιδιών του κόμβου. |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | Ορίζει το σήμανση που αντιπροσωπεύει μόνο τους θυγατρικούς κόμβους αυτού του κόμβου. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Ορίζει το πρόθεμα του χώρου ονομάτων αυτού του κόμβου. |
| void [set_Value](./set_value/)([String](../../system/string/)) override | Ορίζει την τιμή του κόμβου. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό επιχείρημα προτύπου σε αδυναμική αναφορά (αντί για κοινή). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινών αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινών αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [Substring](./substring/)(**int32_t**, **int32_t**) | Ανακτά ένα υποσύνολο της πλήρους συμβολοσειράς από το καθορισμένο εύρος. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Ελέγχει εάν η υλοποίηση DOM υποστηρίζει συγκεκριμένη δυνατότητα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το C# lock() statement ξεκλειδώνοντας. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Λαμβάνει την υλοποίηση του begin const iterator για το τρέχον δοχείο. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Λαμβάνει την υλοποίηση του begin iterator για το τρέχον δοχείο. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Λαμβάνει την υλοποίηση του end const iterator για το τρέχον δοχείο. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Λαμβάνει την υλοποίηση του end iterator για το τρέχον δοχείο. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδυναμικής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδυναμικής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [WriteContentTo](../xmlnode/writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Αποθηκεύει όλους τους θυγατρικούς κόμβους του κόμβου στο καθορισμένο [XmlWriter](../xmlwriter/), όταν υπερκαλύπτεται σε παράγωγη κλάση. |
| virtual void [WriteTo](../xmlnode/writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Αποθηκεύει τον τρέχοντα κόμβο στο καθορισμένο [XmlWriter](../xmlwriter/), όταν υπερκαλύπτεται σε παράγωγη κλάση. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη σε μια παρουσία αυτής της κλάσης. |

## See Also

* Κλάση [XmlLinkedNode](../xmllinkednode/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)