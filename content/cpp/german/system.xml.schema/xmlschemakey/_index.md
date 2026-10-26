---
title: XmlSchemaKey
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Klasse stellt das Schlüssel-Element aus XMLSchema dar, wie vom World Wide Web Consortium (W3C) spezifiziert.
type: docs
weight: 534
url: /de/system.xml.schema/xmlschemakey/
---
## XmlSchemaKey Klasse

Diese Klasse stellt das **key**-Element aus XMLSchema dar, wie vom World Wide [Web](../../system.web/) Consortium (W3C) spezifiziert.

```cpp
class XmlSchemaKey : public System::Xml::Schema::XmlSchemaIdentityConstraint
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Liefert die Eigenschaft **annotation** zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Fields](../xmlschemaidentityconstraint/get_fields/)() | Liefert die Sammlung von Feldern zurück, die als Kinder für den Ausdrucks-Selektor der XML Path Language ([XPath](../../system.xml.xpath/)) gelten. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Liefert die Zeichenketten-ID zurück. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Liefert die Zeilennummer in der Datei zurück, auf die das Element **schema** verweist. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Liefert die Zeilenposition in der Datei zurück, auf die das Element **schema** verweist. |
| [String](../../system/string/) [get_Name](../xmlschemaidentityconstraint/get_name/)() | Liefert den Namen der Identitätsbeschränkung zurück. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Liefert die XmlSerializerNamespaces zurück, die mit diesem Schemaobjekt verwendet werden sollen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Liefert das übergeordnete Element dieses [XmlSchemaObject](../xmlschemaobject/) zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschemaidentityconstraint/get_qualifiedname/)() | Liefert den qualifizierten Namen der Identitätsbeschränkung zurück, der die nach der Kompilierung interpretierte **QualifiedName**-Wert enthält. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\> [get_Selector](../xmlschemaidentityconstraint/get_selector/)() | Liefert das **selector**-Element des Ausdrucks [XPath](../../system.xml.xpath/) zurück. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Liefert den Quellort der Datei zurück, die das Schema geladen hat. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Liefert die qualifizierten Attribute zurück, die nicht zum Ziel-Namespace des aktuellen Schemas gehören. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinelsobjekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Setzt die Eigenschaft **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Setzt die Zeichenketten-ID. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Setzt die Zeilennummer in der Datei, auf die das Element **schema** verweist. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Setzt die Zeilenposition in der Datei, auf die das Element **schema** verweist. |
| void [set_Name](../xmlschemaidentityconstraint/set_name/)(const [String](../../system/string/)\&) | Setzt den Namen der Identitätsbeschränkung. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Setzt die XmlSerializerNamespaces, die mit diesem Schemaobjekt verwendet werden sollen. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Setzt das übergeordnete Element dieses [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Selector](../xmlschemaidentityconstraint/set_selector/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\>\&) | Setzt das **selector**-Element des Ausdrucks [XPath](../../system.xml.xpath/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Setzt den Quellort der Datei, die das Schema geladen hat. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Setzt die qualifizierten Attribute, die nicht zum Ziel-Namespace des aktuellen Schemas gehören. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die geteilte Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinelsobjekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
|  [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/xmlschemaidentityconstraint/)() | Initialisiert eine neue Instanz der Klasse [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialisiert eine neue Instanz der Klasse [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen gemeinsam genutzten Zeiger auf eine Instanz dieser Klasse. |

## Anmerkungen

Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. 

## Siehe auch

* Klasse [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/)
* Namensraum [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)