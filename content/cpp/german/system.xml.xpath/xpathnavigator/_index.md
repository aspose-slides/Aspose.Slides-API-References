---
title: XPathNavigator
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt ein Cursormodell zum Navigieren und Bearbeiten von XML-Daten bereit.
type: docs
weight: 66
url: /de/system.xml.xpath/xpathnavigator/
---
## XPathNavigator Klasse

Stellt ein Cursor-Modell zum Navigieren und Bearbeiten von XML-Daten bereit.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Gibt ein [XmlWriter](../../system.xml/xmlwriter/)-Objekt zurück, das zum Erstellen von einem oder mehreren neuen Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens verwendet wird. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Erstellt einen neuen Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens mit dem angegebenen XML-Datenstring. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Erstellt einen neuen Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens mit dem XML-Inhalt des angegebenen [XmlReader](../../system.xml/xmlreader/)-Objekts. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Erstellt einen neuen Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens unter Verwendung der im angegebenen [XPathNavigator](./) enthaltenen Knoten. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Erstellt einen neuen Kind-Elementknoten am Ende der Liste der Kindknoten des aktuellen Knotens mit dem angegebenen Namespace-Präfix, lokalen Namen und Namespace-URI sowie dem angegebenen Wert. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Überprüft, ob die XML-Daten im [XPathNavigator](./) dem bereitgestellten XML [Schema](../../system.xml.schema/)-Definitionsschema (XSD) entsprechen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Wird in einer abgeleiteten Klasse überschrieben, erstellt ein neues [XPathNavigator](./) am selben Knoten wie dieses [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vergleicht die Position des aktuellen [XPathNavigator](./) mit der Position des angegebenen [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Kompiliert einen String, der einen [XPath](../)-Ausdruck darstellt, und gibt ein [XPathExpression](../xpathexpression/)-Objekt zurück. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Erstellt einen Attributknoten im aktuellen Elementknoten mit dem angegebenen Namespace-Präfix, lokalen Namen, Namespace-URI und dem angegebenen Wert. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Gibt ein [XmlWriter](../../system.xml/xmlwriter/)-Objekt zurück, das zum Erstellen neuer Attribute im aktuellen Element verwendet wird. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Gibt eine Kopie des [XPathNavigator](./) zurück. |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Löscht einen Bereich von Geschwisterknoten vom aktuellen Knoten bis zum angegebenen Knoten. |
| virtual void [DeleteSelf](./deleteself/)() | Löscht den aktuellen Knoten und dessen Kindknoten. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Wertet den angegebenen [XPath](../)-Ausdruck aus und gibt das typisierte Ergebnis zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Wertet den angegebenen [XPath](../)-Ausdruck aus und gibt das typisierte Ergebnis zurück, wobei das angegebene [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-Objekt verwendet wird, um Namespace-Präfixe im [XPath](../)-Ausdruck aufzulösen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Wertet das [XPathExpression](../xpathexpression/) aus und gibt das typisierte Ergebnis zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Verwendet den bereitgestellten Kontext, um das [XPathExpression](../xpathexpression/) auszuwerten, und gibt das typisierte Ergebnis zurück. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert die Basis-URI des aktuellen Knotens. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Gibt einen Wert zurück, der angibt, ob [XPathNavigator](./) die zugrunde liegenden XML-Daten bearbeiten kann. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Gibt einen Wert zurück, der angibt, ob der aktuelle Knoten Attribute besitzt. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Gibt einen Wert zurück, der angibt, ob der aktuelle Knoten Kindknoten hat. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Gibt das Markup zurück, das die Kindknoten des aktuellen Knotens darstellt. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert einen Wert, der angibt, ob der aktuelle Knoten ein leeres Element ohne End-Tag ist. |
| **bool** [get_IsNode](./get_isnode/)() override | Gibt einen Wert zurück, der angibt, ob der aktuelle Knoten ein [XPath](../)-Knoten ist. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert das [XPathNavigator::get_Name](./get_name/) des aktuellen Knotens ohne Namespace-Präfix. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert den qualifizierten Namen des aktuellen Knotens. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert den Namespace-URI des aktuellen Knotens. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert das [XmlNameTable](../../system.xml/xmlnametable/) des [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Gibt ein [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) zurück, das für den Gleichheitsvergleich von [XPathNavigator](./)-Objekten verwendet wird. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert den XPathNodeType des aktuellen Knotens. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Gibt das Markup zurück, das die öffnenden und schließenden Tags des aktuellen Knotens und seiner Kindknoten darstellt. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert das dem aktuellen Knoten zugehörige Namespace-Präfix. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Gibt die Schemainformation zurück, die dem aktuellen Knoten infolge einer Schemagültigkeitsprüfung zugewiesen wurde. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Gibt den aktuellen Knoten als ein gepacktes Objekt des am besten geeigneten Typs zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Wird von [XPathNavigator](./)-Implementierungen genutzt, die eine "virtualisierte" XML-Ansicht über einem Speicher bereitstellen, um Zugriff auf zugrunde liegende Objekte zu gewähren. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Wird in einer abgeleiteten Klasse überschrieben, liefert den **string**-Wert des Elements. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Gibt den Wert des aktuellen Knotens als [Boolean](../../system/boolean/) zurück. |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Gibt den Wert des aktuellen Knotens als [DateTime](../../system/datetime/) zurück. |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Gibt den Wert des aktuellen Knotens als [Double](../../system/double/) zurück. |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Gibt den Wert des aktuellen Knotens als [Int32](../../system/int32/) zurück. |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Gibt den Wert des aktuellen Knotens als [Int64](../../system/int64/) zurück. |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Gibt den Typ des aktuellen Knotens zurück. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Gibt den **xml:lang**-Gültigkeitsbereich des aktuellen Knotens zurück. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Gibt die XmlSchemaType-Information für den aktuellen Knoten zurück. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und Namespace-URI zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Gibt den Wert des Namespace-Knotens zurück, der dem angegebenen lokalen Namen entspricht. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Gibt die im Gültigkeitsbereich befindlichen Namespaces des aktuellen Knotens zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Gibt ein [XmlWriter](../../system.xml/xmlwriter/)-Objekt zurück, das zum Erstellen eines neuen Geschwisterknotens nach dem aktuell ausgewählten Knoten verwendet wird. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Erstellt einen neuen Geschwisterknoten nach dem aktuell ausgewählten Knoten mit dem angegebenen XML-String. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Erstellt einen neuen Geschwisterknoten nach dem aktuell ausgewählten Knoten mit dem XML-Inhalt des angegebenen [XmlReader](../../system.xml/xmlreader/)-Objekts. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Erstellt einen neuen Geschwisterknoten nach dem aktuell ausgewählten Knoten mit den Knoten im angegebenen [XPathNavigator](./)-Objekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Gibt ein [XmlWriter](../../system.xml/xmlwriter/)-Objekt zurück, das zum Erstellen eines neuen Geschwisterknotens vor dem aktuell ausgewählten Knoten verwendet wird. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Erstellt einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten mit dem angegebenen XML-String. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Erstellt einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten mit dem XML-Inhalt des angegebenen [XmlReader](../../system.xml/xmlreader/)-Objekts. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Erstellt einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten mit den Knoten im angegebenen [XPathNavigator](./)-Objekt. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Erstellt ein neues Geschwister-Element nach dem aktuellen Knoten mit dem angegebenen Namespace-Präfix, lokalen Namen und Namespace-URI sowie dem angegebenen Wert. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Erstellt ein neues Geschwister-Element vor dem aktuellen Knoten mit dem angegebenen Namespace-Präfix, lokalen Namen und Namespace-URI sowie dem angegebenen Wert. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Bestimmt, ob das angegebene [XPathNavigator](./) ein Nachkomme des aktuellen [XPathNavigator](./) ist. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Wird in einer abgeleiteten Klasse überschrieben, bestimmt, ob der aktuelle [XPathNavigator](./) dieselbe Position wie das angegebene [XPathNavigator](./) hat. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Gibt den Namespace-URI für das angegebene Präfix zurück. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Gibt das für den angegebenen Namespace-URI deklarierte Präfix zurück. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Bestimmt, ob der aktuelle Knoten dem angegebenen [XPathExpression](../xpathexpression/) entspricht. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Bestimmt, ob der aktuelle Knoten dem angegebenen [XPath](../)-Ausdruck entspricht. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Wird in einer abgeleiteten Klasse überschrieben, verschiebt das [XPathNavigator](./) an dieselbe Position wie das angegebene [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Verschiebt das [XPathNavigator](./) zum Attribut mit dem passenden lokalen Namen und Namespace-URI. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Verschiebt das [XPathNavigator](./) zum Kindknoten mit dem angegebenen lokalen Namen und Namespace-URI. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Verschiebt das [XPathNavigator](./) zum Kindknoten des angegebenen XPathNodeType. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Verschiebt das [XPathNavigator](./) zum ersten Geschwisterknoten des aktuellen Knotens. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Wird in einer abgeleiteten Klasse überschrieben, verschiebt das [XPathNavigator](./) zum ersten Attribut des aktuellen Knotens. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Wird in einer abgeleiteten Klasse überschrieben, verschiebt das [XPathNavigator](./) zum ersten Kindknoten des aktuellen Knotens. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Wird in einer abgeleiteten Klasse überschrieben, verschiebt das [XPathNavigator](./) zum ersten Namespace-Knoten, der dem angegebenen XPathNamespaceScope entspricht. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Bewegt den [XPathNavigator](./) zum ersten Namespace-Knoten des aktuellen Knotens. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Bewegt den [XPathNavigator](./) zum Element mit dem angegebenen lokalen Namen und Namespace-URI in Dokumentreihenfolge. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Bewegt den [XPathNavigator](./) zum Element mit dem angegebenen lokalen Namen und Namespace-URI, zur angegebenen Grenze, in Dokumentreihenfolge. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Bewegt den [XPathNavigator](./) zum folgenden Element des angegebenen XPathNodeType in Dokumentreihenfolge. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Bewegt den [XPathNavigator](./) zum folgenden Element des angegebenen XPathNodeType, zur angegebenen Grenze, in Dokumentreihenfolge. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Beim Überschreiben in einer abgeleiteten Klasse bewegt es sich zum Knoten, der ein Attribut vom Typ **ID** enthält, dessen Wert mit dem angegebenen [String](../../system/string/) übereinstimmt. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Bewegt den [XPathNavigator](./) zum Namespace-Knoten mit dem angegebenen Namespace-Präfix. |
| virtual **bool** [MoveToNext](./movetonext/)() | Beim Überschreiben in einer abgeleiteten Klasse bewegt es den [XPathNavigator](./) zum nächsten Geschwisterknoten des aktuellen Knotens. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Bewegt den [XPathNavigator](./) zum nächsten Geschwisterknoten mit dem angegebenen lokalen Namen und Namespace-URI. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Bewegt den [XPathNavigator](./) zum nächsten Geschwisterknoten des aktuellen Knotens, der dem angegebenen XPathNodeType entspricht. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Beim Überschreiben in einer abgeleiteten Klasse bewegt es den [XPathNavigator](./) zum nächsten Attribut. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Beim Überschreiben in einer abgeleiteten Klasse bewegt es den [XPathNavigator](./) zum nächsten Namespace-Knoten, der dem angegebenen XPathNamespaceScope entspricht. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Bewegt den [XPathNavigator](./) zum nächsten Namespace-Knoten. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Beim Überschreiben in einer abgeleiteten Klasse bewegt es den [XPathNavigator](./) zum Elternknoten des aktuellen Knotens. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Beim Überschreiben in einer abgeleiteten Klasse bewegt es den [XPathNavigator](./) zum vorherigen Geschwisterknoten des aktuellen Knotens. |
| virtual void [MoveToRoot](./movetoroot/)() | Bewegt den [XPathNavigator](./) zum Wurzelknoten, zu dem der aktuelle Knoten gehört. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Gibt ein [XmlWriter](../../system.xml/xmlwriter/)-Objekt zurück, das zum Erstellen eines neuen Kindknotens am Anfang der Kindknotenliste des aktuellen Knotens verwendet wird. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Erstellt einen neuen Kindknoten am Anfang der Kindknotenliste des aktuellen Knotens unter Verwendung des angegebenen XML-Strings. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Erstellt einen neuen Kindknoten am Anfang der Kindknotenliste des aktuellen Knotens unter Verwendung des XML-Inhalts des angegebenen [XmlReader](../../system.xml/xmlreader/)-Objekts. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Erstellt einen neuen Kindknoten am Anfang der Kindknotenliste des aktuellen Knotens unter Verwendung der Knoten im angegebenen [XPathNavigator](./)-Objekt. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Erstellt ein neues Kind-Element am Anfang der Kindknotenliste des aktuellen Knotens unter Verwendung des angegebenen Namespace-Präfixes, lokalen Namens und Namespace-URI mit dem angegebenen Wert. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Gibt ein [XmlReader](../../system.xml/xmlreader/)-Objekt zurück, das den aktuellen Knoten und seine Kindknoten enthält. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ersetzt einen Bereich von Geschwisterknoten vom aktuellen Knoten bis zum angegebenen Knoten. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Ersetzt den aktuellen Knoten durch den Inhalt des angegebenen Strings. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Ersetzt den aktuellen Knoten durch den Inhalt des angegebenen [XmlReader](../../system.xml/xmlreader/)-Objekts. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ersetzt den aktuellen Knoten durch den Inhalt des angegebenen [XPathNavigator](./)-Objekts. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Wählt einen Knotensatz aus, wobei der angegebene [XPath](../)-Ausdruck verwendet wird. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Wählt einen Knotensatz aus, wobei der angegebene [XPath](../)-Ausdruck und das angegebene [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-Objekt zum Auflösen von Namespace-Präfixen verwendet werden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Wählt einen Knotensatz aus, wobei [XPathExpression](../xpathexpression/) verwendet wird. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die zu einem passenden XPathNodeType passen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und Namespace-URI haben. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Wählt alle Kindknoten des aktuellen Knotens aus, die zu einem passenden XPathNodeType passen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Wählt alle Kindknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und Namespace-URI besitzen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Wählt alle Nachfahrenknoten des aktuellen Knotens aus, die zu einem passenden XPathNodeType passen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Wählt alle Nachfahrenknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und Namespace-URI besitzen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Wählt einen einzelnen Knoten im [XPathNavigator](./) anhand der angegebenen [XPath](../)-Abfrage aus. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Wählt einen einzelnen Knoten im [XPathNavigator](./)-Objekt anhand der angegebenen [XPath](../)-Abfrage und dem angegebenen [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-Objekt zum Auflösen von Namespace-Präfixen aus. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Wählt einen einzelnen Knoten im [XPathNavigator](./) anhand des angegebenen [XPathExpression](../xpathexpression/)-Objekts aus. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Setzt das Markup, das die Kindknoten des aktuellen Knotens darstellt. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Setzt das Markup, das die öffnenden und schließenden Tags des aktuellen Knotens und seiner Kindknoten darstellt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt eines Shared-Pointers). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Setzt den typisierten Wert des aktuellen Knotens. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Setzt den Wert des aktuellen Knotens. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointers oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die gemeinsame Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointers oder ThisProtector verwendet werden. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Gibt den Textwert des aktuellen Knotens zurück. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Gibt den Wert des aktuellen Knotens als den angegebenen Typ zurück, wobei das angegebene [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-Objekt zum Auflösen von Namespace-Präfixen verwendet wird. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Gibt den Wert des Elements als den angegebenen Typ zurück. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointers oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointers oder ThisProtector verwendet werden. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Streamt den aktuellen Knoten und seine Kindknoten zu dem angegebenen [XmlWriter](../../system.xml/xmlwriter/)-Objekt. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Siehe Auch

* Klasse [XPathItem](../xpathitem/)
* Klasse [IXPathNavigable](../ixpathnavigable/)
* Klasse [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namensraum [System::Xml::XPath](../)
* Bibliothek [Aspose.Slides](../../)