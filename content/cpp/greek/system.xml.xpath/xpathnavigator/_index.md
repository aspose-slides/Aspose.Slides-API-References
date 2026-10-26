---
title: XPathNavigator
second_title: Aspose.Slides για C++ Αναφορά API
description: Παρέχει ένα μοντέλο κέρσορα για πλοήγηση και επεξεργασία δεδομένων XML.
type: docs
weight: 66
url: /el/system.xml.xpath/xpathnavigator/
---
## XPathNavigator κλάση

Παρέχει ένα μοντέλο κέρσορα για πλοήγηση και επεξεργασία δεδομένων XML.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Επιστρέφει ένα αντικείμενο [XmlWriter](../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός ή περισσότερων νέων κόμβων-παιδιών στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Δημιουργεί έναν νέο κόμβο-παιδί στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά δεδομένων XML. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Δημιουργεί έναν νέο κόμβο-παιδί στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας τα περιεχόμενα XML του καθορισμένου αντικειμένου [XmlReader](../../system.xml/xmlreader/). |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Δημιουργεί έναν νέο κόμβο-παιδί στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας τους κόμβους του καθορισμένου [XPathNavigator](./). |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Δημιουργεί έναν νέο κόμβο στοιχείου-παιδιού στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας το πρόθεμα ονόματος χώρου, το τοπικό όνομα και το URI ονόματος χώρου που καθορίζονται με την τιμή που παρέχεται. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Επαληθεύει ότι τα δεδομένα XML στο [XPathNavigator](./) είναι σύμφωνα με το σχήμα XML [Schema](../../system.xml.schema/) (XSD) που παρέχεται. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, δημιουργεί ένα νέο [XPathNavigator](./) τοποθετημένο στον ίδιο κόμβο με αυτό το [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Συγκρίνει τη θέση του τρέχοντος [XPathNavigator](./) με τη θέση του καθορισμένου [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Συναρτά μια συμβολοσειρά που αντιπροσωπεύει μια έκφραση [XPath](../) και επιστρέφει ένα αντικείμενο [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Δημιουργεί έναν κόμβο χαρακτηριστικού στον τρέχοντα κόμβο στοιχείου χρησιμοποιώντας το πρόθεμα ονόματος χώρου, το τοπικό όνομα και το URI ονόματος χώρου που καθορίζονται με την τιμή που παρέχεται. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Επιστρέφει ένα αντικείμενο [XmlWriter](../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία νέων χαρακτηριστικών στον τρέχοντα στοιχείο. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Επιστρέφει ένα αντίγραφο του [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Διαγράφει ένα εύρος αδελφικών κόμβων από τον τρέχοντα κόμβο έως τον καθορισμένο κόμβο. |
| virtual void [DeleteSelf](./deleteself/)() | Διαγράφει τον τρέχοντα κόμβο και τους κόμβους-παιδιά του. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαίρεσης σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρότι σύμφωνα με IEC 60559:1989 το NaN δεν ισούται με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση διπλής υποδιαίρεσης σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρότι σύμφωνα με IEC 60559:1989 το NaN δεν ισούται με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Αξιολογεί την καθορισμένη έκφραση [XPath](../) και επιστρέφει το τυποποιημένο αποτέλεσμα. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Αξιολογεί την καθορισμένη έκφραση [XPath](../) και επιστρέφει το τυποποιημένο αποτέλεσμα, χρησιμοποιώντας το καθορισμένο αντικείμενο [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) για την επίλυση προθεμάτων ονομάτων χώρου στην έκφραση [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Αξιολογεί το [XPathExpression](../xpathexpression/) και επιστρέφει το τυποποιημένο αποτέλεσμα. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Χρησιμοποιεί το παρεχόμενο συμφρατήντα για την αξιολόγηση του [XPathExpression](../xpathexpression/) και επιστρέφει το τυποποιημένο αποτέλεσμα. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, παίρνει το βασικό URI για τον τρέχοντα κόμβο. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν το [XPathNavigator](./) μπορεί να επεξεργαστεί τα υποκείμενα δεδομένα XML. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν ο τρέχοντος κόμβος διαθέτει χαρακτηριστικά. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Επιστρέφει μια τιμή που υποδεικνύει εάν ο τρέχοντος κόμβος διαθέτει κόμβους-παιδιά. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Επιστρέφει την σήμανση που αντιπροσωπεύει τους κόμβους-παιδιά του τρέχοντος κόμβου. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, παίρνει μια τιμή που υποδεικνύει εάν ο τρέχων κόμβος είναι ένα κενό στοιχείο χωρίς ετικέτα κλεισίματος. |
| **bool** [get_IsNode](./get_isnode/)() override | Επιστρέφει μια τιμή που υποδεικνύει εάν ο τρέχων κόμβος αντιπροσωπεύει έναν κόμβο [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, παίρνει το [XPathNavigator::get_Name](./get_name/) του τρέχοντος κόμβου χωρίς πρόθεμα ονόματος χώρου. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Όταν παρακαμφθεί σε μια παράγωγη κλάση, παίρνει το πλήρες όνομα του τρέχοντος κόμβου. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Όταν παρακαμφθεί σε μια παράγωγη κλάση, παίρνει το URI του ονόματος χώρου του τρέχοντος κόμβου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Όταν παρακαμφθεί σε μια παράγωγη κλάση, παίρνει το [XmlNameTable](../../system.xml/xmlnametable/) του [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Επιστρέφει ένα [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) που χρησιμοποιείται για σύγκριση ισότητας αντικειμένων [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Όταν παρακαμφθεί σε μια παράγωγη κλάση, παίρνει το XPathNodeType του τρέχοντος κόμβου. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Επιστρέφει τη σήμανση που αντιπροσωπεύει τις ετικέτες έναρξης και λήξης του τρέχοντος κόμβου και των κόμβων-παιδιών του. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Όταν παρακαμφθεί σε μια παράγωγη κλάση, παίρνει το πρόθεμα ονόματος χώρου που συνδέεται με τον τρέχοντα κόμβο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Επιστρέφει τις πληροφορίες σχήματος που έχουν εκχωρηθεί στον τρέχοντα κόμβο ως αποτέλεσμα επικύρωσης σχήματος. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Επιστρέφει τον τρέχοντα κόμβο ως ένα boxed αντικείμενο του πιο κατάλληλου τύπου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Χρησιμοποιείται από υλοποιήσεις [XPathNavigator](./) που παρέχουν μια «εικονική» θέα XML πάνω σε αποθηκευτικό χώρο, για να παρέχει πρόσβαση σε υποκείμενα αντικείμενα. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, παίρνει την τιμή **string** του στοιχείου. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Επιστρέφει την τιμή του τρέχοντος κόμβου ως [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Επιστρέφει την τιμή του τρέχοντος κόμβου ως [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Επιστρέφει την τιμή του τρέχοντος κόμβου ως [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Επιστρέφει την τιμή του τρέχοντος κόμβου ως [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Επιστρέφει την τιμή του τρέχοντος κόμβου ως [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Επιστρέφει τον τύπο του τρέχοντος κόμβου. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Επιστρέφει το πεδίο **xml:lang** για τον τρέχοντα κόμβο. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Επιστρέφει τις πληροφορίες XmlSchemaType για τον τρέχοντα κόμβο. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Επιστρέφει την τιμή του χαρακτηριστικού με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Επιστρέφει την τιμή του κόμβου ονόματος χώρου που αντιστοιχεί στο καθορισμένο τοπικό όνομα. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Επιστρέφει τα ονόματα χώρου εντός εμβέλειας του τρέχοντος κόμβου. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Επιστρέφει ένα αντικείμενο [XmlWriter](../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου μετά τον τρέχοντα επιλεγμένο κόμβο. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Δημιουργεί έναν νέο αδελφικό κόμβο μετά τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά XML. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Δημιουργεί έναν νέο αδελφικό κόμβο μετά τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τα περιεχόμενα XML του καθορισμένου αντικειμένου [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Δημιουργεί έναν νέο αδελφικό κόμβο μετά τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τους κόμβους του καθορισμένου αντικειμένου [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Επιστρέφει ένα αντικείμενο [XmlWriter](../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου πριν τον τρέχοντα επιλεγμένο κόμβο. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Δημιουργεί έναν νέο αδελφικό κόμβο πριν τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά XML. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Δημιουργεί έναν νέο αδελφικό κόμβο πριν τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τα περιεχόμενα XML του καθορισμένου αντικειμένου [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Δημιουργεί έναν νέο αδελφικό κόμβο πριν τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τους κόμβους του καθορισμένου [XPathNavigator](./). |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Δημιουργεί έναν νέο αδελφικό στοιχείο-παιδί μετά τον τρέχοντα κόμβο χρησιμοποιώντας το πρόθεμα ονόματος χώρου, το τοπικό όνομα και το URI ονόματος χώρου που καθορίζονται, με την τιμή που παρέχεται. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Δημιουργεί έναν νέο αδελφικό στοιχείο-παιδί πριν τον τρέχοντα κόμβο χρησιμοποιώντας το πρόθεμα ονόματος χώρου, το τοπικό όνομα και το URI ονόματος χώρου που καθορίζονται, με την τιμή που παρέχεται. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# ‘is’. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Καθορίζει εάν το καθορισμένο [XPathNavigator](./) είναι απόγονος του τρέχοντος [XPathNavigator](./). |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Όταν παρακαμφθεί σε παράγωγη κλάση, καθορίζει εάν ο τρέχων [XPathNavigator](./) βρίσκεται στην ίδια θέση με το καθορισμένο [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει τη δήλωση C# lock() για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Επιστρέφει το URI του ονόματος χώρου για το καθορισμένο πρόθεμα. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Επιστρέφει το πρόθεμα που δηλώνεται για το καθορισμένο URI ονόματος χώρου. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Καθορίζει εάν ο τρέχων κόμβος ταιριάζει με το καθορισμένο [XPathExpression](../xpathexpression/). |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Καθορίζει εάν ο τρέχων κόμβος ταιριάζει με το καθορισμένο [XPath](../). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί το cloning προσαρμοσμένων τύπων. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στην ίδια θέση με το καθορισμένο [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Μετακινεί το [XPathNavigator](./) στο χαρακτηριστικό με το αντιστοιχικό τοπικό όνομα και το URI ονόματος χώρου. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Μετακινεί το [XPathNavigator](./) στον κόμβο-παιδί με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Μετακινεί το [XPathNavigator](./) στον κόμβο-παιδί του καθορισμένου XPathNodeType. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Μετακινεί το [XPathNavigator](./) στον πρώτο αδελφικό κόμβο του τρέχοντος κόμβου. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στο πρώτο χαρακτηριστικό του τρέχοντος κόμβου. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στον πρώτο κόμβο-παιδί του τρέχοντος κόμβου. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στον πρώτο κόμβο ονόματος χώρου που ταιριάζει με το καθορισμένο XPathNamespaceScope. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Μετακινεί το [XPathNavigator](./) στον πρώτο κόμβο ονόματος χώρου του τρέχοντος κόμβου. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Μετακινεί το [XPathNavigator](./) στο στοιχείο με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου σε σειρά εγγράφου. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Μετακινεί το [XPathNavigator](./) στο στοιχείο με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου, στο όριο που καθορίζεται, σε σειρά εγγράφου. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Μετακινεί το [XPathNavigator](./) στο επόμενο στοιχείο του καθορισμένου XPathNodeType σε σειρά εγγράφου. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Μετακινεί το [XPathNavigator](./) στο επόμενο στοιχείο του καθορισμένου XPathNodeType, στο όριο που καθορίζεται, σε σειρά εγγράφου. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινείται στον κόμβο που έχει χαρακτηριστικό τύπου **ID** με τιμή που ταιριάζει με το καθορισμένο [String](../../system/string/). |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Μετακινεί το [XPathNavigator](./) στον κόμβο ονόματος χώρου με το καθορισμένο πρόθεμα ονόματος χώρου. |
| virtual **bool** [MoveToNext](./movetonext/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στον επόμενο αδελφικό κόμβο του τρέχοντος κόμβου. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Μετακινεί το [XPathNavigator](./) στον επόμενο αδελφικό κόμβο με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Μετακινεί το [XPathNavigator](./) στον επόμενο αδελφικό κόμβο του τρέχοντος κόμβου που ταιριάζει με το καθορισμένο XPathNodeType. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στο επόμενο χαρακτηριστικό. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στον επόμενο κόμβο ονόματος χώρου που ταιριάζει με το καθορισμένο XPathNamespaceScope. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Μετακινεί το [XPathNavigator](./) στον επόμενο κόμβο ονόματος χώρου. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στον γονικό κόμβο του τρέχοντος κόμβου. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Όταν παρακαμφθεί σε παράγωγη κλάση, μετακινεί το [XPathNavigator](./) στον προηγούμενο αδελφικό κόμβο του τρέχοντος κόμβου. |
| virtual void [MoveToRoot](./movetoroot/)() | Μετακινεί το [XPathNavigator](./) στον ριζικό κόμβο που ανήκει ο τρέχων κόμβος. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει κατασκευή αντιγραφής σε παράγωγες κλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει κατασκευή αντιγραφής σε παράγωγες κλάσεις. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Επιστρέφει ένα αντικείμενο [XmlWriter](../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου κόμβου-παιδιού στην αρχή της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Δημιουργεί έναν νέο κόμβο-παιδί στην αρχή της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά XML. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Δημιουργεί έναν νέο κόμβο-παιδί στην αρχή της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας τα περιεχόμενα XML του καθορισμένου αντικειμένου [XmlReader](../../system.xml/xmlreader/). |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Δημιουργεί έναν νέο κόμβο-παιδί στην αρχή της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας τους κόμβους του καθορισμένου αντικειμένου [XPathNavigator](./). |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Δημιουργεί ένα νέο στοιχείο-παιδί στην αρχή της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας το πρόθεμα ονόματος χώρου, το τοπικό όνομα και το URI ονόματος χώρου που καθορίζονται με την τιμή που παρέχεται. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Επιστρέφει ένα αντικείμενο [XmlReader](../../system.xml/xmlreader/) που περιέχει τον τρέχοντα κόμβο και τους κόμβους-παιδιά του. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Αντικαθιστά ένα εύρος αδελφικών κόμβων από τον τρέχοντα κόμβο έως τον καθορισμένο κόμβο. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Αντικαθιστά τον τρέχοντα κόμβο με το περιεχόμενο της καθορισμένης συμβολοσειράς. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Αντικαθιστά τον τρέχοντα κόμβο με τα περιεχόμενα του καθορισμένου αντικειμένου [XmlReader](../../system.xml/xmlreader/). |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Αντικαθιστά τον τρέχοντα κόμβο με τα περιεχόμενα του καθορισμένου αντικειμένου [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Επιλέγει σύνολο κόμβων, χρησιμοποιώντας την καθορισμένη έκφραση [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Επιλέγει σύνολο κόμβων χρησιμοποιώντας την καθορισμένη έκφραση [XPath](../) με το αντικείμενο [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) για την επίλυση προθεμάτων ονομάτων χώρου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Επιλέγει σύνολο κόμβων χρησιμοποιώντας το καθορισμένο [XPathExpression](../xpathexpression/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Επιλέγει όλους τους προγενέστερους κόμβους του τρέχοντος κόμβου που έχουν το αντίστοιχο XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Επιλέγει όλους τους προγενέστερους κόμβους του τρέχοντος κόμβου που έχουν το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Επιλέγει όλους τους κόμβους-παιδιά του τρέχοντος κόμβου που έχουν το αντίστοιχο XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Επιλέγει όλους τους κόμβους-παιδιά του τρέχοντος κόμβου που έχουν το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Επιλέγει όλους τους απογόνους κόμβους του τρέχοντος κόμβου που έχουν το αντίστοιχο XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Επιλέγει όλους τους απογόνους κόμβους του τρέχοντος κόμβου με το καθορισμένο τοπικό όνομα και URI ονόματος χώρου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Επιλέγει έναν μοναδικό κόμβο στο [XPathNavigator](./) χρησιμοποιώντας το καθορισμένο ερώτημα [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Επιλέγει έναν μοναδικό κόμβο στο αντικείμενο [XPathNavigator](./) χρησιμοποιώντας το καθορισμένο ερώτημα [XPath](../) με το αντικείμενο [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) για την επίλυση προθεμάτων ονομάτων χώρου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Επιλέγει έναν μοναδικό κόμβο στο [XPathNavigator](./) χρησιμοποιώντας το καθορισμένο αντικείμενο [XPathExpression](../xpathexpression/). |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Ορίζει τη σήμανση που αντιπροσωπεύει τους κόμβους-παιδιά του τρέχοντος κόμβου. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Ορίζει τη σήμανση που αντιπροσωπεύει τις ετικέτες έναρξης και λήξης του τρέχοντος κόμβου και των κόμβων-παιδιών του. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατό δείκτη (αντί για shared). Επιτρέπει αλλαγή δεικτών σε containers σε αδυνατό τρόπο. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ορίζει την τυποποιημένη τιμή του τρέχοντος κόμβου. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Ορίζει την τιμή του τρέχοντος κόμβου. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει το μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει το μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Επιστρέφει την τιμή κειμένου του τρέχοντος κόμβου. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί τη δήλωση C# lock() για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Επιστρέφει την τιμή του τρέχοντος κόμβου ως τον καθορισμένο τύπο, χρησιμοποιώντας το αντικείμενο [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) για την επίλυση προθεμάτων ονομάτων χώρου. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Επιστρέφει την τιμή του στοιχείου ως τον καθορισμένο τύπο. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το μετρητή αδυνατών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το μετρητή αδυνατών αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Μεταφέρει τον τρέχοντα κόμβο και τους κόμβους-παιδιά του στο αντικείμενο [XmlWriter](../../system.xml/xmlwriter/) που καθορίζεται. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |
## Τύποι

| Τύπος | Περιγραφή |
| --- | --- |
| [Ptr](./ptr/) | Ένα ψευδώνυμο για shared pointer σε μια παρουσία αυτής της κλάσης. |
## Δείτε επίσης

* Class [XPathItem](../xpathitem/)
* Class [IXPathNavigable](../ixpathnavigable/)
* Class [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)