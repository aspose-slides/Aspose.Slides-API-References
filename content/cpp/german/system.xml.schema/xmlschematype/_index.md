---
title: XmlSchemaType
second_title: Aspose.Slides für C++ API-Referenz
description: Die Basisklasse für alle einfachen Typen und komplexen Typen.
type: docs
weight: 911
url: /de/system.xml.schema/xmlschematype/
---
## XmlSchemaType Klasse


Die Basisklasse für alle einfachen Typen und komplexen Typen.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Gibt die **annotation**-Eigenschaft zurück. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](./get_baseschematype/)() | Gibt den nach der Kompilierung erstellten Objekttyp oder den integrierten XML [Schema](../) Definition Language (XSD) Datentyp, das simpleType-Element oder das complexType-Element zurück. Dies ist ein nach Schema-Kompilierung erstellter Infoset-Wert. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\> [get_BaseXmlSchemaType](./get_basexmlschematype/)() | Gibt den nach der Kompilierung erstellten Wert für den Basistyp dieses Schematyps zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](./get_datatype/)() | Gibt den nach der Kompilierung erstellten Wert für den Datentyp des komplexen Typs zurück. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](./get_derivedby/)() | Gibt die nach der Kompilierung erstellte Information darüber zurück, wie dieses Element von seinem Basistyp abgeleitet wurde. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Gibt das finale Attribut der Typableitung zurück, das angibt, ob weitere Ableitungen erlaubt sind. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Gibt die nach der Kompilierung erstellte Interpretation des [XmlSchemaType::get_Final](./get_final/)-Werts zurück. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Gibt die Zeichenketten-ID zurück. |
| virtual **bool** [get_IsMixed](./get_ismixed/)() | Gibt einen Wert zurück, der angibt, ob dieser Typ ein gemischtes Inhaltsmodell besitzt. Dieser Aufruf ist nur in einem komplexen Typ zulässig. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Gibt die Zeilennummer in der Datei zurück, auf die das **schema**-Element verweist. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Gibt die Zeilenposition in der Datei zurück, auf die das **schema**-Element verweist. |
| [String](../../system/string/) [get_Name](./get_name/)() | Gibt den Namen des Typs zurück. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Gibt die XmlSerializerNamespaces zurück, die mit diesem Schemaobjekt verwendet werden sollen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Gibt das übergeordnete Element dieses [XmlSchemaObject](../xmlschemaobject/) zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Gibt den qualifizierten Namen für den Typ zurück, der aus dem **Name**-Attribut dieses Typs erstellt wurde. Dies ist ein nach Schema-Kompilierung erstellter Wert. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Gibt den Quellort für die Datei zurück, die das Schema geladen hat. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | Gibt den XmlTypeCode des Typs zurück. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Gibt die qualifizierten Attribute zurück, die nicht zum Ziel-Namensraum des aktuellen Schemas gehören. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Gibt ein [XmlSchemaComplexType](../xmlschemacomplextype/) zurück, das den integrierten komplexen Typ des angegebenen komplexen Typs darstellt. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Gibt ein [XmlSchemaComplexType](../xmlschemacomplextype/) zurück, das den integrierten komplexen Typ des durch qualifizierten Namen angegebenen komplexen Typs darstellt. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Gibt ein [XmlSchemaSimpleType](../xmlschemasimpletype/) zurück, das den integrierten einfachen Typ des einfachen Typs zurückgibt, der durch den qualifizierten Namen angegeben ist. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Gibt ein [XmlSchemaSimpleType](../xmlschemasimpletype/) zurück, das den integrierten einfachen Typ des angegebenen einfachen Typs darstellt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
| static **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Gibt einen Wert zurück, der angibt, ob der angegebene abgeleitete Schematyp vom angegebenen Basisschematyp abgeleitet ist. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert wirklich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert wirklich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht den Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Setzt die **annotation**-Eigenschaft. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Setzt das finale Attribut der Typableitung, das angibt, ob weitere Ableitungen erlaubt sind. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Setzt die Zeichenketten-ID. |
| virtual void [set_IsMixed](./set_ismixed/)(**bool**) | Setzt einen Wert, der angibt, ob dieser Typ ein gemischtes Inhaltsmodell besitzt. Dieser Aufruf ist nur in einem komplexen Typ zulässig. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Setzt die Zeilennummer in der Datei, auf die das **schema**-Element verweist. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Setzt die Zeilenposition in der Datei, auf die das **schema**-Element verweist. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Setzt den Namen des Typs. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Setzt die XmlSerializerNamespaces, die mit diesem Schemaobjekt verwendet werden sollen. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Setzt das übergeordnete Element dieses [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Setzt den Quellort für die Datei, die das Schema geladen hat. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Setzt die qualifizierten Attribute, die nicht zum Ziel-Namensraum des aktuellen Schemas gehören. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsam genutzten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsam genutzten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialisiert eine neue Instanz der [XmlSchemaObject](../xmlschemaobject/)-Klasse. |
|  [XmlSchemaType](./xmlschematype/)() | Initialisiert eine neue Instanz der [XmlSchemaType](./)-Klasse. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Anmerkungen

Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Pointer ein und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben. 

## Siehe auch

* Klasse [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namensraum [System::Xml::Schema](../)
* Bibliothek [Aspose.Slides](../../)