---
title: XmlSchemaAttribute
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta l'elemento attributo dello schema XML specificato dal World Wide Web Consortium (W3C). Gli attributi forniscono informazioni aggiuntive per gli altri elementi del documento. Il tag attributo è annidato tra i tag dell'elemento di un documento per lo schema. Il documento XML visualizza gli attributi come elementi nominati nel tag di apertura di un elemento.
type: docs
weight: 170
url: /it/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute classe

Rappresenta l'elemento **attributo** dall'XML [Schema](../) così come specificato dal Consorzio World Wide [Web](../../system.web/) (W3C). Gli attributi forniscono informazioni aggiuntive per gli altri elementi del documento. Il tag dell'attributo è annidato tra i tag di un elemento del documento per lo schema. Il documento XML visualizza gli attributi come elementi nominati nel tag di apertura di un elemento.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti utilizzando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Restituisce la proprietà **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_AttributeSchemaType](./get_attributeschematype/)() | Restituisce un oggetto [XmlSchemaSimpleType](../xmlschemasimpletype/) che rappresenta il tipo dell'attributo basato sul valore [XmlSchemaAttribute::get_SchemaType](./get_schematype/) o [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) dell'attributo. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_AttributeType](./get_attributetype/)() | Restituisce l'oggetto basato sul valore [XmlSchemaAttribute::get_SchemaType](./get_schematype/) o [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) dell'attributo che contiene l'interpretazione post-compilazione del valore **AttributeType**. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Restituisce il valore predefinito per l'attributo. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Restituisce il valore fisso per l'attributo. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Restituisce la forma per l'attributo. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Restituisce l'ID stringa. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Restituisce il numero di riga nel file a cui l'elemento **schema** fa riferimento. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Restituisce la posizione di riga nel file a cui l'elemento **schema** fa riferimento. |
| [String](../../system/string/) [get_Name](./get_name/)() | Restituisce il nome dell'attributo. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Restituisce gli XmlSerializerNamespaces da usare con questo oggetto schema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Restituisce il genitore di questo [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Restituisce il nome qualificato per l'attributo. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Restituisce il nome di un attributo dichiarato in questo schema (o in un altro schema indicato dallo spazio dei nomi specificato). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_SchemaType](./get_schematype/)() | Restituisce il tipo di attributo a un tipo semplice. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Restituisce il nome del tipo semplice definito in questo schema (o in un altro schema indicato dallo spazio dei nomi specificato). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Restituisce la posizione di origine per il file che ha caricato lo schema. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Restituisce gli attributi qualificati che non appartengono allo spazio dei nomi di destinazione dello schema corrente. |
| [XmlSchemaUse](../xmlschemause/) [get_Use](./get_use/)() | Restituisce informazioni su come viene usato l'attributo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Imposta la proprietà **annotation**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Imposta il valore predefinito per l'attributo. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Imposta il valore fisso per l'attributo. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Imposta la forma per l'attributo. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Imposta l'ID stringa. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Imposta il numero di riga nel file a cui l'elemento **schema** fa riferimento. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Imposta la posizione di riga nel file a cui l'elemento **schema** fa riferimento. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Imposta il nome dell'attributo. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Imposta gli XmlSerializerNamespaces da usare con questo oggetto schema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Imposta il genitore di questo [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Imposta il nome di un attributo dichiarato in questo schema (o in un altro schema indicato dallo spazio dei nomi specificato). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | Imposta il tipo di attributo a un tipo semplice. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Imposta il nome del tipo semplice definito in questo schema (o in un altro schema indicato dallo spazio dei nomi specificato). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Imposta la posizione di origine per il file che ha caricato lo schema. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Imposta gli attributi qualificati che non appartengono allo spazio dei nomi di destinazione dello schema corrente. |
| void [set_Use](./set_use/)([XmlSchemaUse](../xmlschemause/)) | Imposta le informazioni su come viene usato l'attributo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
|  [XmlSchemaAttribute](./xmlschemaattribute/)() | Inizializza una nuova istanza della classe [XmlSchemaAttribute](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inizializza una nuova istanza della classe [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | Un alias per puntatore condiviso a un'istanza di questa classe. |

## Osservazioni

Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarla alle funzioni come argomento. 

## Vedi anche

* Classe [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Libreria [Aspose.Slides](../../)