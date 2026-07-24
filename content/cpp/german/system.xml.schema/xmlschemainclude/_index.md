---
title: XmlSchemaInclude
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das include element aus dem XML Schema dar, wie vom World Wide Web Consortium (W3C) festgelegt. Diese Klasse wird verwendet, um Deklarationen und Definitionen aus einem externen Schema einzuschließen. Die eingeschlossenen Deklarationen und Definitionen stehen anschließend für die Verarbeitung im umgebenden Schema zur Verfügung.
type: docs
weight: 495
url: /de/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude Klasse


Represents the **include** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is used to include declarations and definitions from an external schema. The included declarations and definitions are then available for processing in the containing schema.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](./get_annotation/)() | Gibt den **annotation**-Wert zurück. |
| [String](../../system/string/) [get_Id](../xmlschemaexternal/get_id/)() | Gibt die Zeichenkette id zurück. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Gibt die Zeilennummer in der Datei zurück, auf die sich das **schema**-Element bezieht. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Gibt die Zeilenposition in der Datei zurück, auf die sich das **schema**-Element bezieht. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Gibt die XmlSerializerNamespaces zurück, die mit diesem Schema-Objekt verwendet werden sollen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Gibt das übergeordnete Element dieses [XmlSchemaObject](../xmlschemaobject/) zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [get_Schema](../xmlschemaexternal/get_schema/)() | Gibt das [XmlSchema](../xmlschema/) für das referenzierte Schema zurück. |
| [String](../../system/string/) [get_SchemaLocation](../xmlschemaexternal/get_schemalocation/)() | Gibt den Uniform Resource Identifier (URI) für das Schema zurück, der dem Schema-Prozessor mitteilt, wo das Schema physisch liegt. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Gibt den Quellort der Datei zurück, die das Schema geladen hat. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaexternal/get_unhandledattributes/)() | Gibt die qualifizierten Attribute zurück, die nicht zum Ziel-Namensraum des Schemas gehören. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Annotation](./set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Setzt den **annotation**-Wert. |
| void [set_Id](../xmlschemaexternal/set_id/)(const [String](../../system/string/)\&) | Setzt die Zeichenkette id. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Setzt die Zeilennummer in der Datei, auf die sich das **schema**-Element bezieht. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Setzt die Zeilenposition in der Datei, auf die sich das **schema**-Element bezieht. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Setzt die XmlSerializerNamespaces, die mit diesem Schema-Objekt verwendet werden sollen. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Setzt das übergeordnete Element dieses [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Schema](../xmlschemaexternal/set_schema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Setzt das [XmlSchema](../xmlschema/) für das referenzierte Schema. |
| void [set_SchemaLocation](../xmlschemaexternal/set_schemalocation/)(const [String](../../system/string/)\&) | Setzt den Uniform Resource Identifier (URI) für das Schema, der dem Schema-Prozessor mitteilt, wo das Schema physisch liegt. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Setzt den Quellort der Datei, die das Schema geladen hat. |
| void [set_UnhandledAttributes](../xmlschemaexternal/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Setzt die qualifizierten Attribute, die nicht zum Ziel-Namensraum des Schemas gehören. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument als schwachen Zeiger (statt shared). Erlaubt das Umstellen von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
|  [XmlSchemaExternal](../xmlschemaexternal/xmlschemaexternal/)() | Initialisiert eine neue Instanz der [XmlSchemaExternal](../xmlschemaexternal/)-Klasse. |
|  [XmlSchemaInclude](./xmlschemainclude/)() | Initialisiert eine neue Instanz der [XmlSchemaInclude](./)-Klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialisiert eine neue Instanz der [XmlSchemaObject](../xmlschemaobject/)-Klasse. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |
## Anmerkungen



Objekte dieser Klasse sollten nur mittels der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. 

## Siehe auch

* Klasse [XmlSchemaExternal](../xmlschemaexternal/)
* Namensraum [System::Xml::Schema](../)
* Bibliothek [Aspose.Slides](../../)