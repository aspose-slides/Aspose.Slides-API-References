---
title: XmlEntity
second_title: Αναφορά API του Aspose.Slides για C++
description: Αντιπροσωπεύει μια δήλωση οντότητας, όπως <!ENTITY... >.
type: docs
weight: 235
url: /el/system.xml/xmlentity/
---
## XmlEntity κλάση

Αντιπροσωπεύει μια δήλωση οντότητας, όπως **<!ENTITY... >**.

```cpp
class XmlEntity : public System::Xml::XmlNode
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Προσθέτει τον καθορισμένο κόμβο στο τέλος της λίστας των θυγατρικών κόμβων αυτού του κόμβου. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο (αν υπάρχει) της συλλογής. Αυτός ο επαναλήπτης δεν μπορεί να χρησιμοποιηθεί για την αλλαγή του αναφερόμενου αντικειμένου επειδή το [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) επιστρέφει ένα αντίγραφο του T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο (αν υπάρχει) της σταθερά-καθορισμένης έκδοσης της συλλογής. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο που είναι σταθερά-καθορισμένο (αν υπάρχει) της συλλογής. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει αμέσως μετά το τελευταίο στοιχείο που είναι σταθερά-καθορισμένο (αν υπάρχει) της συλλογής. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Δημιουργεί ένα αντίγραφο αυτού του κόμβου. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Δημιουργεί ένα αντίγραφο αυτού του κόμβου. Οι κόμβοι οντότητας δεν μπορούν να κλωνοποιηθούν. Η κλήση αυτής της μεθόδου σε ένα αντικείμενο [XmlEntity](./) προκαλεί εξαίρεση. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Δημιουργεί ένα XPathNavigator για την περιήγηση σε αυτό το αντικείμενο. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Επιστρέφει έναν επαναλήπτη που δείχνει αμέσως μετά το τελευταίο στοιχείο (αν υπάρχει) της συλλογής. Αυτός ο επαναλήπτης δεν μπορεί να χρησιμοποιηθεί για την αλλαγή του αναφερόμενου αντικειμένου επειδή το [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) επιστρέφει ένα αντίγραφο του T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει αμέσως μετά το τελευταίο στοιχείο (αν υπάρχει) της σταθερά-καθορισμένης έκδοσης της συλλογής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με το στυλ του C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με το στυλ του C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητών σημείων τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητών σημείων τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Επιστρέφει ένα [XmlAttributeCollection](../xmlattributecollection/) που περιέχει τα χαρακτηριστικά αυτού του κόμβου. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Επιστρέφει το βασικό Uniform Resource Identifier (URI) του τρέχοντος κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Επιστρέφει όλους τους θυγατρικούς κόμβους του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Επιστρέφει το πρώτο παιδί του κόμβου. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Επιστρέφει τιμή που υποδεικνύει εάν αυτός ο κόμβος έχει οποιουσδήποτε θυγατρικούς κόμβους. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | Επιστρέφει τις συγχωνευμένες τιμές του κόμβου οντότητας και όλων των παιδιών του. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Επιστρέφει το markup που αντιπροσωπεύει τα παιδιά αυτού του κόμβου. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | Επιστρέφει τιμή που υποδεικνύει εάν ο κόμβος είναι μόνο-ανάγνωση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Επιστρέφει το τελευταίο παιδί του κόμβου. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Επιστρέφει το όνομα του κόμβου χωρίς το πρόθεμα του ονοματοχώρου. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Επιστρέφει το όνομα του κόμβου. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Επιστρέφει το URI του ονοματοχώρου αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Επιστρέφει τον κόμβο που ακολουθεί αμέσως αυτόν τον κόμβο. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Επιστρέφει τον τύπο του κόμβου. |
| [String](../../system/string/) [get_NotationName](./get_notationname/)() | Επιστρέφει το όνομα του προαιρετικού χαρακτηριστικού NDATA στη δήλωση οντότητας. |
| [String](../../system/string/) [get_OuterXml](./get_outerxml/)() override | Επιστρέφει το markup που αντιπροσωπεύει αυτόν τον κόμβο και όλα τα παιδιά του. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Επιστρέφει το [XmlDocument](../xmldocument/) στο οποίο ανήκει αυτός ο κόμβος. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Επιστρέφει τον γονέα αυτού του κόμβου (για κόμβους που μπορούν να έχουν γονείς). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Επιστρέφει το πρόθεμα του ονοματοχώρου αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Επιστρέφει τον κόμβο που προηγείται αμέσως αυτού του κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Επιστρέφει τον κόμβο κειμένου που προηγείται αμέσως αυτού του κόμβου. |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | Επιστρέφει την τιμή του δημόσιου αναγνωριστικού στη δήλωση οντότητας. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Επιστρέφει το σύνολο πληροφοριών μετά την επικύρωση σχήματος που έχει ανατεθεί σε αυτόν τον κόμβο ως αποτέλεσμα της επικύρωσης σχήματος. |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | Επιστρέφει την τιμή του αναγνωριστικού συστήματος στη δήλωση οντότητας. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Επιστρέφει την τιμή του κόμβου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Επιστρέφει έναν ενομετρητή που διατρέχει τους θυγατρικούς κόμβους του τρέχοντος κόμβου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική του C# [Object.GetHashCode()](../../system/object/gethashcode/) μεθόδου. Επιτρέπει τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Αναζητά τη κοντινότερη δήλωση **xmlns** για το δοσμένο πρόθεμα που είναι εντός εμβέλειας του τρέχοντος κόμβου και επιστρέφει το URI του ονοματοχώρου στη δήλωση. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Αναζητά τη κοντινότερη δήλωση **xmlns** για το δοσμένο URI ονοματοχώρου που είναι εντός εμβέλειας του τρέχοντος κόμβου και επιστρέφει το πρόθεμα που ορίζεται σε αυτή τη δήλωση. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Επιστρέφει το πρώτο στοιχείο-παιδί με το καθορισμένο [XmlNode::get_Name](../xmlnode/get_name/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Επιστρέφει το πρώτο στοιχείο-παιδί με τις καθορισμένες τιμές [XmlNode::get_LocalName](../xmlnode/get_localname/) και [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Εισάγει τον καθορισμένο κόμβο αμέσως μετά τον καθορισμένο κόμβο αναφοράς. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Εισάγει τον καθορισμένο κόμβο αμέσως πριν τον καθορισμένο κόμβο αναφοράς. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει μια συνάρτηση συσσωρευτή πάνω σε μια ακολουθία. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει εάν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Καθορίζει εάν μια ακολουθία περιέχει στοιχεία. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει εάν υπάρχει κάποιο στοιχείο στην ακολουθία ή αν ικανοποιεί μια συνθήκη. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Μετατρέπει (cast) τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Συνενώνει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Καθορίζει εάν μια ακολουθία περιέχει τη συγκεκριμένη τιμή. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενο μέσω άμεσης μέτρησης). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν τη συγκεκριμένη συνθήκη. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί τη συγκεκριμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας, ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή εάν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας, ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη ελάχιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας με βάση τον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιών που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιών που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Αναστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Μετασχηματίζει τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν καθορισμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου κατηγορητή. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική του C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) μεθόδου. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| virtual void [Normalize](../xmlnode/normalize/)() | Τοποθετεί όλους τους κόμβους [XmlText](../xmltext/) σε πλήρη βάθος του υποδέντρου κάτω από αυτόν τον [XmlNode](../xmlnode/) σε μια "κανονική" μορφή όπου μόνο το markup (δηλαδή ετικέτες, σχόλια, οδηγίες επεξεργασίας, ενότητες CDATA και αναφορές οντότητας) διαχωρίζει τους κόμβους [XmlText](../xmltext/), δηλαδή δεν υπάρχουν γειτονικοί κόμβοι [XmlText](../xmltext/). |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Προσθέτει τον καθορισμένο κόμβο στην αρχή της λίστας των θυγατρικών κόμβων για αυτόν τον κόμβο. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα βάσει αναφοράς. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα βάσει αναφοράς. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά ενός αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Καταργεί όλους τους θυγατρικούς κόμβους και/ή τα χαρακτηριστικά του τρέχοντος κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Καταργεί τον καθορισμένο θυγατρικό κόμβο. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Αντικαθιστά τον θυγατρικό κόμβο **oldChild** με τον κόμβο **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Επιλέγει μια λίστα κόμβων που ταιριάζουν με την έκφραση [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Επιλέγει μια λίστα κόμβων που ταιριάζουν με την έκφραση [XPath](../../system.xml.xpath/). Όλα τα προθέματα που εντοπίζονται στην έκφραση [XPath](../../system.xml.xpath/) επιλύονται χρησιμοποιώντας το παρεχόμενο [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Επιλέγει το πρώτο [XmlNode](../xmlnode/) που ταιριάζει με την έκφραση [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Επιλέγει το πρώτο [XmlNode](../xmlnode/) που ταιριάζει με την έκφραση [XPath](../../system.xml.xpath/). Τα προθέματα που βρίσκονται στην έκφραση [XPath](../../system.xml.xpath/) επιλύονται με το παρεχόμενο [XmlNamespaceManager](../xmlnamespacemanager/). |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Ορίζει τις συγχωνευμένες τιμές του κόμβου οντότητας και όλων των παιδιών του. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Ορίζει το markup που αντιπροσωπεύει τα παιδιά αυτού του κόμβου. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Ορίζει το πρόθεμα του ονοματοχώρου αυτού του κόμβου. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Ορίζει την τιμή του κόμβου. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Δοκιμάζει εάν η υλοποίηση DOM υποστηρίζει μια συγκεκριμένη δυνατότητα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική του C# [Object.ToString()](../../system/object/tostring/) μεθόδου. Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το C# typeof([System.Object](../../system/object/)) κατασκεύασμα. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Λαμβάνει την υλοποίηση του begin const επαναλήπτη για το τρέχον κοντέινερ. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Λαμβάνει την υλοποίηση του begin επαναλήπτη για το τρέχον κοντέινερ. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Λαμβάνει την υλοποίηση του end const επαναλήπτη για το τρέχον κοντέινερ. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Λαμβάνει την υλοποίηση του end επαναλήπτη για το τρέχον κοντέινερ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνες δείκτες ή ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Αποθηκεύει όλα τα παιδιά του κόμβου στο καθορισμένο [XmlWriter](../xmlwriter/). Για κόμβους [XmlEntity](./), αυτή η μέθοδος δεν έχει καμία επίδραση. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Αποθηκεύει τον κόμβο στο καθορισμένο [XmlWriter](../xmlwriter/). Για κόμβους [XmlEntity](./), αυτή η μέθοδος δεν έχει καμία επίδραση. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Ορισμοί τύπων

| Typedef | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για κοινό δείκτη σε ένα στιγμιότυπο αυτής της κλάσης. |

## Παρατηρήσεις

Αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο με τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπα αυτού του τύπου στη στοίβα ή με τον τελεστή new, καθώς αυτό οδηγεί σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα.

## Δείτε επίσης

* Κλάση [XmlNode](../xmlnode/)
* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)