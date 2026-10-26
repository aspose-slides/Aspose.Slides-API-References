---
title: XmlSchemaElement
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta l'elemento element dallo Schema XML come specificato dal World Wide Web Consortium (W3C). Questa classe è la classe base per tutti i tipi di particella ed è usata per descrivere un elemento in un documento XML.
type: docs
weight: 365
url: /it/system.xml.schema/xmlschemaelement/
---
## classe XmlSchemaElement

Rappresenta l'elemento **element** da XML [Schema](../) come specificato dal Consorzio World Wide [Web](../../system.web/) (W3C). Questa classe è la classe base per tutti i tipi di particella ed è usata per descrivere un elemento in un documento XML.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Metodi

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Restituisce la proprietà **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Restituisce una derivazione **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Restituisce l'interpretazione post-compilazione del valore **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Restituisce la raccolta di vincoli sull'elemento. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Restituisce il valore predefinito dell'elemento se il suo contenuto è un tipo semplice o il contenuto dell'elemento è **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Restituisce un oggetto [XmlSchemaType](../xmlschematype/) che rappresenta il tipo dell'elemento basato sui valori [XmlSchemaElement::get_SchemaType](./get_schematype/) o [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) dell'elemento. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Restituisce un oggetto basato su [XmlSchemaElement](./) o [XmlSchemaElement](./) dell'elemento, che contiene l'interpretazione post-compilazione del valore **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Restituisce il valore **Final** per indicare che non sono ammesse ulteriori derivazioni. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Restituisce l'interpretazione post-compilazione del valore **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Restituisce il valore fisso. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Restituisce la forma per l'elemento. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Restituisce l'id stringa. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Restituisce informazioni per indicare se l'elemento può essere usato in un documento di istanza. |
| **bool** [get_IsNillable](./get_isnillable/)() | Restituisce informazioni che indicano se **xsi:nil** può comparire nei dati di istanza. Indica se un valore nil esplicito può essere assegnato all'elemento. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Restituisce il numero di riga nel file a cui si riferisce l'elemento **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Restituisce la posizione di colonna nel file a cui si riferisce l'elemento **schema**. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Restituisce il numero massimo di volte in cui la particella può verificarsi. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Restituisce il numero come valore stringa. Numero massimo di volte in cui la particella può verificarsi. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Restituisce il numero minimo di volte in cui la particella può verificarsi. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Restituisce il numero come valore stringa. Numero minimo di volte in cui la particella può verificarsi. |
| [String](../../system/string/) [get_Name](./get_name/)() | Restituisce il nome dell'elemento. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Restituisce gli XmlSerializerNamespaces da usare con questo oggetto schema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Restituisce il genitore di questo [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Restituisce il nome qualificato reale per l'elemento fornito. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Restituisce il nome di riferimento di un elemento dichiarato in questo schema (o in un altro schema indicato dallo spazio dei nomi specificato). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Restituisce il tipo dell'elemento. Può essere un tipo complesso o un tipo semplice. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Restituisce il nome di un tipo di dato incorporato definito in questo schema o in un altro schema indicato dallo spazio dei nomi specificato. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Restituisce la posizione di origine per il file che ha caricato lo schema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Restituisce il nome di un elemento che è sostituito da questo elemento. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Restituisce gli attributi qualificati che non appartengono allo spazio dei nomi di destinazione dello schema corrente. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associato all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if\<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>\::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if\<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>\::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Imposta la proprietà **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Imposta una derivazione **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Imposta il valore predefinito dell'elemento se il suo contenuto è un tipo semplice o il contenuto dell'elemento è **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Imposta il valore **Final** per indicare che non sono ammesse ulteriori derivazioni. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Imposta il valore fisso. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Imposta la forma per l'elemento. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Imposta l'id stringa. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Imposta le informazioni per indicare se l'elemento può essere usato in un documento di istanza. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Imposta le informazioni che indicano se **xsi:nil** può comparire nei dati di istanza. Indica se un valore nil esplicito può essere assegnato all'elemento. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Imposta il numero di riga nel file a cui si riferisce l'elemento **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Imposta la posizione di colonna nel file a cui si riferisce l'elemento **schema**. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Imposta il numero massimo di volte in cui la particella può verificarsi. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Imposta il numero come valore stringa. Numero massimo di volte in cui la particella può verificarsi. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Imposta il numero minimo di volte in cui la particella può verificarsi. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Imposta il numero come valore stringa. Numero minimo di volte in cui la particella può verificarsi. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Imposta il nome dell'elemento. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Imposta gli XmlSerializerNamespaces da usare con questo oggetto schema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Imposta il genitore di questo [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Imposta il nome di riferimento di un elemento dichiarato in questo schema (o in un altro schema indicato dallo spazio dei nomi specificato). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Imposta il tipo dell'elemento. Può essere un tipo complesso o un tipo semplice. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Imposta il nome di un tipo di dato incorporato definito in questo schema o in un altro schema indicato dallo spazio dei nomi specificato. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Imposta la posizione di origine per il file che ha caricato lo schema. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Imposta il nome di un elemento che è sostituito da questo elemento. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Imposta gli attributi qualificati che non appartengono allo spazio dei nomi di destinazione dello schema corrente. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| [XmlSchemaElement](./xmlschemaelement/)() | Inizializza una nuova istanza della classe [XmlSchemaElement](./). |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inizializza una nuova istanza della classe [XmlSchemaObject](../xmlschemaobject/). |
| [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Inizializza una nuova istanza della classe [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedef

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias per puntatore condiviso a un'istanza di questa classe. |

## Note

Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò causerebbe errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. 

## Vedi anche

* Classe [XmlSchemaParticle](../xmlschemaparticle/)
* Spazio dei nomi [System::Xml::Schema](../)
* Libreria [Aspose.Slides](../../)