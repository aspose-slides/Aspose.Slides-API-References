---
title: XmlSignificantWhitespace
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt Leerzeichen zwischen Markup in einem gemischten Inhaltsknoten oder Leerzeichen innerhalb eines xml:space='preserve'-Bereichs dar. Dies wird ebenfalls als signifikante Leerzeichen bezeichnet."
type: docs
weight: 482
url: /de/system.xml/xmlsignificantwhitespace/
---
## XmlSignificantWhitespace Klasse

Stellt Leerzeichen zwischen Markup in einem gemischten Inhaltsknoten oder Leerzeichen innerhalb eines **xml:space='preserve'**-Bereichs dar. Dies wird ebenfalls als signifikante Leerzeichen bezeichnet.

```cpp
class XmlSignificantWhitespace : public System::Xml::XmlCharacterData
```

## Methoden

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Fügt den angegebenen Knoten am Ende der Liste von Kindknoten dieses Knotens hinzu. |
| virtual void [AppendData](../xmlcharacterdata/appenddata/)([String](../../system/string/)) | Fügt die angegebene Zeichenfolge an das Ende der Zeichendaten des Knotens an. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Liefert einen Iterator, der auf das erste Element (falls vorhanden) der Sammlung zeigt. Dieser Iterator kann nicht verwendet werden, um ein referenziertes Objekt zu ändern, da [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) ein Kopie-Objekt von T zurückgibt. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Liefert einen Iterator, der auf das erste Element (falls vorhanden) der const-qualifizierten Instanz der Sammlung zeigt. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Liefert einen Iterator, der auf das erste const-qualifizierte Element (falls vorhanden) der Sammlung zeigt. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Liefert einen Iterator, der direkt nach dem letzten const-qualifizierten Element (falls vorhanden) der Sammlung zeigt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Erstellt ein Duplikat dieses Knotens. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Erstellt ein Duplikat dieses Knotens. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Erstellt einen XPathNavigator zum Navigieren dieses Objekts. |
| virtual void [DeleteData](../xmlcharacterdata/deletedata/)(**int32_t**, **int32_t**) | Entfernt einen Zeichenbereich aus dem Knoten. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Liefert einen Iterator, der direkt nach dem letzten Element (falls vorhanden) der Sammlung zeigt. Dieser Iterator kann nicht verwendet werden, um ein referenziertes Objekt zu ändern, da [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) ein Kopie-Objekt von T zurückgibt. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Liefert einen Iterator, der direkt nach dem letzten Element (falls vorhanden) der const-qualifizierten Instanz der Sammlung zeigt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung von C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Gibt ein [XmlAttributeCollection](../xmlattributecollection/) zurück, das die Attribute dieses Knotens enthält. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Gibt die Basis-URI des aktuellen Knotens zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Gibt alle Kindknoten des Knotens zurück. |
| virtual [String](../../system/string/) [get_Data](../xmlcharacterdata/get_data/)() | Gibt die Daten des Knotens zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Gibt das erste Kind des Knotens zurück. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Gibt einen Wert zurück, der angibt, ob dieser Knoten Kindknoten besitzt. |
| [String](../../system/string/) [get_InnerText](../xmlcharacterdata/get_innertext/)() override | Gibt die verketteten Werte des Knotens und aller seiner Kindknoten zurück. |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | Gibt das Markup zurück, das nur die Kindknoten dieses Knotens darstellt. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Gibt einen Wert zurück, der angibt, ob der Knoten schreibgeschützt ist. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Gibt das letzte Kind des Knotens zurück. |
| virtual **int32_t** [get_Length](../xmlcharacterdata/get_length/)() | Gibt die Länge der Daten in Zeichen zurück. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Gibt den lokalen Namen des Knotens zurück. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Gibt den qualifizierten Namen des Knotens zurück. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Gibt die Namespace-URI dieses Knotens zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Gibt den Knoten zurück, der unmittelbar auf diesen Knoten folgt. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Gibt den Typ des aktuellen Knotens zurück. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Gibt das Markup zurück, das diesen Knoten und alle seine Kindknoten enthält. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Gibt das [XmlDocument](../xmldocument/) zurück, zu dem dieser Knoten gehört. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Gibt das übergeordnete Element dieses Knotens zurück (für Knoten, die über Eltern verfügen können). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Gibt das Namespace-Präfix dieses Knotens zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Gibt den Knoten zurück, der unmittelbar vor diesem Knoten liegt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](./get_previoustext/)() override | Gibt den Textknoten zurück, der unmittelbar vor diesem Knoten liegt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Gibt das nach der Schema-Validierung zugewiesene Infoset zurück, das diesem Knoten als Ergebnis der Schema-Validierung zugewiesen wurde. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Gibt den Wert des Knotens zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Gibt einen Enumerator zurück, der die Kindknoten des aktuellen Knotens durchläuft. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Sucht die nächstgelegene **xmlns**-Deklaration für das angegebene Präfix, das im Geltungsbereich des aktuellen Knotens liegt, und gibt die Namespace-URI in der Deklaration zurück. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Sucht die nächstgelegene **xmlns**-Deklaration für die angegebene Namespace-URI, die im Geltungsbereich des aktuellen Knotens liegt, und gibt das in dieser Deklaration definierte Präfix zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Gibt das erste Kind-Element mit dem angegebenen [XmlNode::get_Name](../xmlnode/get_name/) zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Gibt das erste Kind-Element mit den angegebenen [XmlNode::get_LocalName](../xmlnode/get_localname/)- und [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/)-Werten zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Fügt den angegebenen Knoten unmittelbar nach dem angegebenen Referenzknoten ein. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Fügt den angegebenen Knoten unmittelbar vor dem angegebenen Referenzknoten ein. |
| virtual void [InsertData](../xmlcharacterdata/insertdata/)(**int32_t**, [String](../../system/string/)) | Fügt die angegebene Zeichenfolge an der angegebenen Zeichenposition ein. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Wendet eine Akkumulatorfunktion auf eine Sequenz an. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestimmt, ob alle Elemente einer Sequenz eine Bedingung erfüllen. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bestimmt, ob eine Sequenz Elemente enthält. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestimmt, ob irgendein Element einer Sequenz existiert oder eine Bedingung erfüllt. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Berechnet den Durchschnitt einer Sequenz numerischer Werte. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Berechnet den Durchschnitt einer Sequenz von Werten, die durch Aufrufen einer Transformationsfunktion auf jedes Element der Eingabesequenz erhalten werden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Wandelt die Elemente in den angegebenen Typ um. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Verkettet zwei Sequenzen. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bestimmt, ob eine Sequenz einen angegebenen Wert enthält. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Gibt die Anzahl der Elemente in der Sequenz zurück (berechnet durch direkte Zählung). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Gibt die Anzahl der Elemente in der Sequenz zurück, die die angegebene Bedingung erfüllen. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Gibt das Element an einem angegebenen Index in einer Sequenz zurück. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Gibt das Element an einem angegebenen Index in einer Sequenz zurück. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Gibt das erste Element einer Sequenz zurück. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Gibt das erste Element einer Sequenz zurück, das die angegebene Bedingung erfüllt. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Gibt das erste Element einer Sequenz zurück, oder einen Standardwert, wenn die Sequenz leer ist. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Gibt das erste Element der Sequenz zurück, das eine Bedingung erfüllt, oder einen Standardwert, wenn kein solches Element gefunden wird. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Gruppiert die Elemente einer Sequenz. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Gruppiert die Elemente einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Gibt das letzte Element einer Sequenz zurück. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Gibt das letzte Element einer Sequenz zurück, oder einen Standardwert, wenn die Sequenz leer ist. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den maximalen resultierenden Wert zurück. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den minimalen resultierenden Wert zurück. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtert die Elemente der Sequenz basierend auf dem angegebenen Typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortiert die Elemente einer Sequenz aufsteigend nach den vom keySelector ausgewählten Schlüsselwerten. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortiert die Elemente einer Sequenz absteigend nach den vom keySelector ausgewählten Schlüsselwerten. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Kehrt die Reihenfolge der Elemente in einer Sequenz um. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformiert Elemente einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformiert jedes Element einer Sequenz in eine neue Form, indem der Index des Elements einbezogen wird. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektiert jedes Element einer Sequenz und kombiniert die resultierenden Sequenzen zu einer einzigen Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Überspringt eine angegebene Anzahl zusammenhängender Elemente am Anfang einer Sequenz und gibt den Rest zurück. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Gibt eine angegebene Anzahl zusammenhängender Elemente am Anfang einer Sequenz zurück. |
| [System::ArrayPtr](../../system/arrayptr/)\<T> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Erstellt ein Array aus einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Erstellt eine List<T> aus einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert eine Sequenz basierend auf dem angegebenen Prädikat. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| virtual void [Normalize](../xmlnode/normalize/)() | Setzt alle [XmlText](../xmltext/)-Knoten in der vollen Tiefe des Unterbaums unterhalb dieses [XmlNode](../xmlnode/) in eine „normale“ Form, bei der nur Markup (d. h. Tags, Kommentare, Verarbeitungshinweise, CDATA-Abschnitte und Entity-Referenzen) [XmlText](../xmltext/)-Knoten trennt, d. h. es gibt keine benachbarten [XmlText](../xmltext/)-Knoten. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Fügt den angegebenen Knoten am Anfang der Liste von Kindknoten dieses Knotens hinzu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Entfernt alle Kindknoten und/oder Attribute des aktuellen Knotens. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Entfernt den angegebenen Kindknoten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Ersetzt den Kindknoten **oldChild** durch den **newChild**-Knoten. |
| virtual void [ReplaceData](../xmlcharacterdata/replacedata/)(**int32_t**, **int32_t**, [String](../../system/string/)) | Ersetzt die angegebene Anzahl von Zeichen ab dem angegebenen Offset durch die angegebene Zeichenfolge. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Wählt eine Liste von Knoten aus, die dem [XPath](../../system.xml.xpath/)-Ausdruck entsprechen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Wählt eine Liste von Knoten aus, die dem [XPath](../../system.xml.xpath/)-Ausdruck entsprechen. Alle im [XPath](../../system.xml.xpath/)-Ausdruck gefundenen Präfixe werden mit dem bereitgestellten [XmlNamespaceManager](../xmlnamespacemanager/) aufgelöst. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Wählt das erste [XmlNode](../xmlnode/) aus, das dem [XPath](../../system.xml.xpath/)-Ausdruck entspricht. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Wählt das erste [XmlNode](../xmlnode/) aus, das dem [XPath](../../system.xml.xpath/)-Ausdruck entspricht. Alle im [XPath](../../system.xml.xpath/)-Ausdruck gefundenen Präfixe werden mit dem bereitgestellten [XmlNamespaceManager](../xmlnamespacemanager/) aufgelöst. |
| virtual void [set_Data](../xmlcharacterdata/set_data/)([String](../../system/string/)) | Setzt die Daten des Knotens. |
| void [set_InnerText](../xmlcharacterdata/set_innertext/)([String](../../system/string/)) override | Setzt die verketteten Werte des Knotens und aller seiner Kindknoten. |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | Setzt das Markup, das nur die Kindknoten dieses Knotens darstellt. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Setzt das Namespace-Präfix dieses Knotens. |
| void [set_Value](./set_value/)([String](../../system/string/)) override | Setzt den Wert des Knotens. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [Substring](../xmlcharacterdata/substring/)(**int32_t**, **int32_t**) | Ruft eine Teilzeichenkette des gesamten Strings aus dem angegebenen Bereich ab. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Testet, ob die DOM-Implementierung ein bestimmtes Feature unterstützt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Ermittelt die Implementierung des begin-const-Iterators für den aktuellen Container. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Ermittelt die Implementierung des begin-Iterators für den aktuellen Container. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Ermittelt die Implementierung des end-const-Iterators für den aktuellen Container. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Ermittelt die Implementierung des end-Iterators für den aktuellen Container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Speichert alle Kindknoten des Knotens im angegebenen [XmlWriter](../xmlwriter/). |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Speichert den Knoten im angegebenen [XmlWriter](../xmlwriter/). |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |

## Hinweise

Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. 

## Siehe auch

* Klasse [XmlCharacterData](../xmlcharacterdata/)
* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)