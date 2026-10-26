---
title: XPathNavigator
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce un modello di cursore per la navigazione e la modifica dei dati XML.
type: docs
weight: 66
url: /it/system.xml.xpath/xpathnavigator/
---
## XPathNavigator classe

Fornisce un modello di cursore per navigare e modificare dati XML.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Restituisce un oggetto [XmlWriter](../../system.xml/xmlwriter/) utilizzato per creare uno o più nuovi nodi figlio alla fine dell'elenco dei nodi figlio del nodo corrente. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Crea un nuovo nodo figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando la stringa di dati XML specificata. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuovo nodo figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando il contenuto XML dell'oggetto [XmlReader](../../system.xml/xmlreader/) specificato. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuovo nodo figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando i nodi presenti in [XPathNavigator](./) specificato. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuovo nodo elemento figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando il prefisso di spazio dei nomi, il nome locale e l'URI di spazio dei nomi specificati con il valore indicato. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Verifica che i dati XML in [XPathNavigator](./) siano conformi allo schema del linguaggio di definizione XML [Schema](../../system.xml.schema/) (XSD) fornito. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Quando sovrascritto in una classe derivata, crea un nuovo [XPathNavigator](./) posizionato allo stesso nodo di questo [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Confronta la posizione del [XPathNavigator](./) corrente con la posizione del [XPathNavigator](./) specificato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Compila una stringa che rappresenta un'espressione [XPath](../) e restituisce un oggetto [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nodo attributo sul nodo elemento corrente utilizzando il prefisso di spazio dei nomi, il nome locale e l'URI di spazio dei nomi specificati con il valore indicato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Restituisce un oggetto [XmlWriter](../../system.xml/xmlwriter/) usato per creare nuovi attributi sull'elemento corrente. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Restituisce una copia del [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Elimina un intervallo di nodi fratelli dal nodo corrente fino al nodo specificato. |
| virtual void [DeleteSelf](./deleteself/)() | Elimina il nodo corrente e i suoi nodi figlio. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Valuta l'espressione [XPath](../) specificata e restituisce il risultato tipizzato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Valuta l'espressione [XPath](../) specificata e restituisce il risultato tipizzato, usando l'oggetto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi di spazio dei nomi nell'espressione [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Valuta il [XPathExpression](../xpathexpression/) e restituisce il risultato tipizzato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Utilizza il contesto fornito per valutare il [XPathExpression](../xpathexpression/) e restituisce il risultato tipizzato. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Quando sovrascritto in una classe derivata, ottiene l'URI di base per il nodo corrente. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Restituisce un valore che indica se [XPathNavigator](./) può modificare i dati XML sottostanti. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Restituisce un valore che indica se il nodo corrente ha attributi. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Restituisce un valore che indica se il nodo corrente ha nodi figlio. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Restituisce il markup che rappresenta i nodi figlio del nodo corrente. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Quando sovrascritto in una classe derivata, ottiene un valore che indica se il nodo corrente è un elemento vuoto senza tag di chiusura. |
| **bool** [get_IsNode](./get_isnode/)() override | Restituisce un valore che indica se il nodo corrente rappresenta un nodo [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Quando sovrascritto in una classe derivata, ottiene il [XPathNavigator::get_Name](./get_name/) del nodo corrente senza alcun prefisso di spazio dei nomi. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Quando sovrascritto in una classe derivata, ottiene il nome qualificato del nodo corrente. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Quando sovrascritto in una classe derivata, ottiene l'URI di spazio dei nomi del nodo corrente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Quando sovrascritto in una classe derivata, ottiene il [XmlNameTable](../../system.xml/xmlnametable/) del [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Restituisce un [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) usato per il confronto di uguaglianza degli oggetti [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Quando sovrascritto in una classe derivata, ottiene lo XPathNodeType del nodo corrente. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Restituisce il markup che rappresenta i tag di apertura e chiusura del nodo corrente e dei suoi nodi figlio. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Quando sovrascritto in una classe derivata, ottiene il prefisso di spazio dei nomi associato al nodo corrente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Restituisce le informazioni di schema assegnate al nodo corrente a seguito della validazione dello schema. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Restituisce il nodo corrente come oggetto incapsulato del tipo più appropriato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Usato dalle implementazioni [XPathNavigator](./) che forniscono una vista XML "virtualizzata" su uno store, per fornire l'accesso agli oggetti sottostanti. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Quando sovrascritto in una classe derivata, ottiene il valore **string** dell'elemento. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Restituisce il valore del nodo corrente come [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Restituisce il valore del nodo corrente come [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Restituisce il valore del nodo corrente come [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Restituisce il valore del nodo corrente come [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Restituisce il valore del nodo corrente come [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Restituisce il tipo del nodo corrente. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Restituisce l'ambito **xml:lang** per il nodo corrente. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Restituisce le informazioni XmlSchemaType per il nodo corrente. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Restituisce il valore dell'attributo con il nome locale e l'URI di spazio dei nomi specificati. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Restituisce il valore del nodo di spazio dei nomi corrispondente al nome locale specificato. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Restituisce gli spazi dei nomi in ambito del nodo corrente. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Restituisce un oggetto [XmlWriter](../../system.xml/xmlwriter/) usato per creare un nuovo nodo fratello dopo il nodo attualmente selezionato. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Crea un nuovo nodo fratello dopo il nodo attualmente selezionato usando la stringa XML specificata. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuovo nodo fratello dopo il nodo attualmente selezionato usando il contenuto XML dell'oggetto [XmlReader](../../system.xml/xmlreader/) specificato. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuovo nodo fratello dopo il nodo attualmente selezionato usando i nodi nell'oggetto [XPathNavigator](./) specificato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Restituisce un oggetto [XmlWriter](../../system.xml/xmlwriter/) usato per creare un nuovo nodo fratello prima del nodo attualmente selezionato. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Crea un nuovo nodo fratello prima del nodo attualmente selezionato usando la stringa XML specificata. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuovo nodo fratello prima del nodo attualmente selezionato usando il contenuto XML dell'oggetto [XmlReader](../../system.xml/xmlreader/) specificato. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuovo nodo fratello prima del nodo attualmente selezionato usando i nodi nell'oggetto [XPathNavigator](./) specificato. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuovo elemento fratello dopo il nodo corrente usando il prefisso di spazio dei nomi, il nome locale e l'URI di spazio dei nomi specificati, con il valore indicato. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuovo elemento fratello prima del nodo corrente usando il prefisso di spazio dei nomi, il nome locale e l'URI di spazio dei nomi specificati, con il valore indicato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Determina se il [XPathNavigator](./) specificato è discendente del [XPathNavigator](./) corrente. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Quando sovrascritto in una classe derivata, determina se il [XPathNavigator](./) corrente è nella stessa posizione del [XPathNavigator](./) specificato. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Restituisce l'URI di spazio dei nomi per il prefisso specificato. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Restituisce il prefisso dichiarato per l'URI di spazio dei nomi specificato. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Determina se il nodo corrente corrisponde al [XPathExpression](../xpathexpression/) specificato. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Determina se il nodo corrente corrisponde all'espressione [XPath](../) specificata. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Quando sovrascritto in una classe derivata, sposta il [XPathNavigator](./) nella stessa posizione del [XPathNavigator](./) specificato. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Sposta il [XPathNavigator](./) sull'attributo con il nome locale e l'URI di spazio dei nomi corrispondenti. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Sposta il [XPathNavigator](./) sul nodo figlio con il nome locale e l'URI di spazio dei nomi specificati. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Sposta il [XPathNavigator](./) sul nodo figlio del XPathNodeType specificato. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Sposta il [XPathNavigator](./) sul primo nodo fratello del nodo corrente. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Quando sovrascritto in una classe derivata, sposta il [XPathNavigator](./) sul primo attributo del nodo corrente. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Quando sovrascritto in una classe derivata, sposta il [XPathNavigator](./) sul primo nodo figlio del nodo corrente. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Quando sovrascritto in una classe derivata, sposta il [XPathNavigator](./) sul primo nodo di spazio dei nomi che corrisponde allo XPathNamespaceScope specificato. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Sposta il [XPathNavigator](./) al primo nodo namespace del nodo corrente. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Sposta il [XPathNavigator](./) all'elemento con il nome locale e l'URI del namespace specificati nell'ordine del documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Sposta il [XPathNavigator](./) all'elemento con il nome locale e l'URI del namespace specificati, al confine specificato, nell'ordine del documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Sposta il [XPathNavigator](./) all'elemento successivo del XPathNodeType specificato nell'ordine del documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Sposta il [XPathNavigator](./) all'elemento successivo del XPathNodeType specificato, al confine specificato, nell'ordine del documento. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Quando viene sovrascritto in una classe derivata, sposta al nodo che ha un attributo di tipo **ID** il cui valore corrisponde al [String](../../system/string/) specificato. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Sposta il [XPathNavigator](./) al nodo namespace con il prefisso namespace specificato. |
| virtual **bool** [MoveToNext](./movetonext/)() | Quando viene sovrascritto in una classe derivata, sposta il [XPathNavigator](./) al nodo fratello successivo del nodo corrente. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Sposta il [XPathNavigator](./) al nodo fratello successivo con il nome locale e l'URI del namespace specificati. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Sposta il [XPathNavigator](./) al nodo fratello successivo del nodo corrente che corrisponde al XPathNodeType specificato. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Quando viene sovrascritto in una classe derivata, sposta il [XPathNavigator](./) al prossimo attributo. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Quando viene sovrascritto in una classe derivata, sposta il [XPathNavigator](./) al prossimo nodo namespace che corrisponde allo XPathNamespaceScope specificato. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Sposta il [XPathNavigator](./) al prossimo nodo namespace. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Quando viene sovrascritto in una classe derivata, sposta il [XPathNavigator](./) al nodo genitore del nodo corrente. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Quando viene sovrascritto in una classe derivata, sposta il [XPathNavigator](./) al nodo fratello precedente del nodo corrente. |
| virtual void [MoveToRoot](./movetoroot/)() | Sposta il [XPathNavigator](./) al nodo radice a cui appartiene il nodo corrente. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle subclassi. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Restituisce un oggetto [XmlWriter](../../system.xml/xmlwriter/) utilizzato per creare un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Crea un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando la stringa XML specificata. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando il contenuto XML dell'oggetto [XmlReader](../../system.xml/xmlreader/) specificato. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando i nodi nell'oggetto [XPathNavigator](./) specificato. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuovo elemento figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando il prefisso namespace, il nome locale e l'URI del namespace specificati con il valore specificato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Restituisce un oggetto [XmlReader](../../system.xml/xmlreader/) che contiene il nodo corrente e i suoi nodi figlio. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Sostituisce un intervallo di nodi fratelli dal nodo corrente al nodo specificato. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Sostituisce il nodo corrente con il contenuto della stringa specificata. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Sostituisce il nodo corrente con il contenuto dell'oggetto [XmlReader](../../system.xml/xmlreader/) specificato. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Sostituisce il nodo corrente con il contenuto dell'oggetto [XPathNavigator](./) specificato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Seleziona un insieme di nodi, usando l'espressione [XPath](../) specificata. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Seleziona un insieme di nodi usando l'espressione [XPath](../) specificata con l'oggetto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi dei namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Seleziona un insieme di nodi usando il [XPathExpression](../xpathexpression/) specificato. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Seleziona tutti i nodi ancestro del nodo corrente che hanno un XPathNodeType corrispondente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Seleziona tutti i nodi ancestro del nodo corrente che hanno il nome locale e l'URI del namespace specificati. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Seleziona tutti i nodi figlio del nodo corrente che hanno un XPathNodeType corrispondente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Seleziona tutti i nodi figlio del nodo corrente che hanno il nome locale e l'URI del namespace specificati. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Seleziona tutti i nodi discendente del nodo corrente che hanno un XPathNodeType corrispondente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Seleziona tutti i nodi discendente del nodo corrente con il nome locale e l'URI del namespace specificati. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Seleziona un singolo nodo in [XPathNavigator](./) usando la query [XPath](../) specificata. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Seleziona un singolo nodo nell'oggetto [XPathNavigator](./) usando la query [XPath](../) specificata con l'oggetto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi dei namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Seleziona un singolo nodo in [XPathNavigator](./) usando l'oggetto [XPathExpression](../xpathexpression/) specificato. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Imposta il markup che rappresenta i nodi figlio del nodo corrente. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Imposta il markup che rappresenta i tag di apertura e chiusura del nodo corrente e dei suoi nodi figlio. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n'th argomento del modello a un puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Imposta il valore tipizzato del nodo corrente. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Imposta il valore del nodo corrente. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Restituisce il valore di testo del nodo corrente. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Restituisce il valore del nodo corrente come il Tipo specificato, usando l'oggetto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi dei namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Restituisce il valore dell'elemento come il tipo specificato. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Trasmette il nodo corrente e i suoi nodi figlio all'oggetto [XmlWriter](../../system.xml/xmlwriter/) specificato. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Definizioni di tipo

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | Un alias per puntatore condiviso a un'istanza di questa classe. |
## Vedi anche

* Classe [XPathItem](../xpathitem/)
* Classe [IXPathNavigable](../ixpathnavigable/)
* Classe [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../)
* Libreria [Aspose.Slides](../../)