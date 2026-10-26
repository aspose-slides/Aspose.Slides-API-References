---
title: XmlSchemaElement
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Element-Element aus dem XML-Schema dar, wie vom World Wide Web Consortium (W3C) spezifiziert. Diese Klasse ist die Basisklasse für alle Partikeltypen und wird verwendet, um ein Element in einem XML-Dokument zu beschreiben.
type: docs
weight: 365
url: /de/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement Klasse


Represents the **element** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is the base class for all particle types and is used to describe an element in an XML document.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Für interne Zwecke only. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Gibt die **annotation**-Eigenschaft zurück. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Gibt eine **Block**-Ableitung zurück. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Gibt die nach der Kompilierung interpretierte **Block**-Wert-Interpretation zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Gibt die Menge der Einschränkungen für das Element zurück. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Gibt den Standardwert des Elements zurück, falls sein Inhalt ein einfacher Typ ist oder der Inhalt des Elements **textOnly** ist. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Gibt ein [XmlSchemaType](../xmlschematype/)-Objekt zurück, das den Typ des Elements basierend auf den [XmlSchemaElement::get_SchemaType](./get_schematype/)- oder [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/)-Werten des Elements darstellt. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Gibt ein Objekt zurück, das auf dem [XmlSchemaElement](./)- oder [XmlSchemaElement](./)-Wert des Elements basiert und die nach der Kompilierung interpretierte **ElementType**-Wert enthält. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Gibt den **Final**-Wert zurück, um anzuzeigen, dass keine weiteren Ableitungen erlaubt sind. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Gibt die nach der Kompilierung interpretierte **Final**-Wert-Interpretation zurück. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Gibt den festen Wert zurück. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Gibt die Form des Elements zurück. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Gibt die Zeichenketten-ID zurück. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Gibt Informationen zurück, die angeben, ob das Element in einem Instanzdokument verwendet werden kann. |
| **bool** [get_IsNillable](./get_isnillable/)() | Gibt Informationen zurück, die angeben, ob **xsi:nil** in den Instanzdaten auftreten kann. Gibt an, ob dem Element ein expliziter Nil-Wert zugewiesen werden kann. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Gibt die Zeilennummer in der Datei zurück, auf die das **schema**-Element verweist. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Gibt die Zeilenposition in der Datei zurück, auf die das **schema**-Element verweist. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Gibt die maximale Anzahl an, wie oft das Partikel auftreten darf. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Gibt die Zahl als Zeichenfolge zurück. Maximale Anzahl, wie oft das Partikel auftreten darf. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Gibt die minimale Anzahl an, wie oft das Partikel auftreten darf. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Gibt die Zahl als Zeichenfolge zurück. Minimale Anzahl, wie oft das Partikel auftreten darf. |
| [String](../../system/string/) [get_Name](./get_name/)() | Gibt den Namen des Elements zurück. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Gibt die XmlSerializerNamespaces zurück, die mit diesem Schema-Objekt verwendet werden sollen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Gibt das übergeordnete [XmlSchemaObject](../xmlschemaobject/) zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Gibt den tatsächlichen qualifizierten Namen für das angegebene Element zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Gibt den Referenznamen eines im Schema (oder einem anderen durch den angegebenen Namensraum angegebenen Schema) deklarierten Elements zurück. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Gibt den Typ des Elements zurück. Dies kann ein komplexer Typ oder ein einfacher Typ sein. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Gibt den Namen eines im Schema (oder einem anderen durch den angegebenen Namensraum definierten) eingebauten Datentyps zurück. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Gibt den Quellort der Datei zurück, die das Schema geladen hat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Gibt den Namen eines Elements zurück, das durch dieses Element ersetzt wird. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Gibt die qualifizierten Attribute zurück, die nicht zum Zielnamensraum des aktuellen Schemas gehören. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-[Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Setzt die **annotation**-Eigenschaft. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Setzt eine **Block**-Ableitung. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Setzt den Standardwert des Elements, falls sein Inhalt ein einfacher Typ ist oder der Inhalt des Elements **textOnly** ist. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Setzt den **Final**-Wert, um anzuzeigen, dass keine weiteren Ableitungen erlaubt sind. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Setzt den festen Wert. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Setzt die Form des Elements. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Setzt die Zeichenketten-ID. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Setzt Informationen, die angeben, ob das Element in einem Instanzdokument verwendet werden kann. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Setzt Informationen, die angeben, ob **xsi:nil** in den Instanzdaten auftreten kann. Gibt an, ob dem Element ein expliziter Nil-Wert zugewiesen werden kann. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Setzt die Zeilennummer in der Datei, auf die das **schema**-Element verweist. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Setzt die Zeilenposition in der Datei, auf die das **schema**-Element verweist. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Setzt die maximale Anzahl, wie oft das Partikel auftreten darf. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Setzt die Zahl als Zeichenfolge. Maximale Anzahl, wie oft das Partikel auftreten darf. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Setzt die minimale Anzahl, wie oft das Partikel auftreten darf. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Setzt die Zahl als Zeichenfolge. Minimale Anzahl, wie oft das Partikel auftreten darf. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Setzt den Namen des Elements. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Setzt die XmlSerializerNamespaces, die mit diesem Schema-Objekt verwendet werden sollen. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Setzt das übergeordnete [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Setzt den Referenznamen eines im Schema (oder einem anderen durch den angegebenen Namensraum angegebenen Schema) deklarierten Elements. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Setzt den Typ des Elements. Dies kann ein komplexer Typ oder ein einfacher Typ sein. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Setzt den Namen eines im Schema (oder einem anderen durch den angegebenen Namensraum definierten) eingebauten Datentyps. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Setzt den Quellort der Datei, die das Schema geladen hat. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Setzt den Namen eines Elements, das durch dieses Element ersetzt wird. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Setzt die qualifizierten Attribute, die nicht zum Zielnamensraum des aktuellen Schemas gehören. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umstellen von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des gemeinsamen Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [XmlSchemaElement](./xmlschemaelement/)() | Initialisiert eine neue Instanz der [XmlSchemaElement](./)-Klasse. |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialisiert eine neue Instanz der [XmlSchemaObject](../xmlschemaobject/)-Klasse. |
| [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Initialisiert eine neue Instanz der [XmlSchemaParticle](../xmlschemaparticle/)-Klasse. |
| virtual [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Hinweise



Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. 

## Siehe auch

* Klasse [XmlSchemaParticle](../xmlschemaparticle/)
* Namensraum [System::Xml::Schema](../)
* Bibliothek [Aspose.Slides](../../)