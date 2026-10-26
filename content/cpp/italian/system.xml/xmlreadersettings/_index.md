---
title: XmlReaderSettings
second_title: Riferimento API Aspose.Slides per C++
description: "Specifica un insieme di funzionalità da supportare sull'oggetto XmlReader creato dal metodo XmlReader::Create."
type: docs
weight: 443
url: /it/system.xml/xmlreadersettings/
---
## XmlReaderSettings classe

Specifica un insieme di funzionalità da supportare sull'oggetto [XmlReader](../xmlreader/) creato dal metodo [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Metodi

| Method | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Crea una copia dell'istanza [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Restituisce un valore che indica se eseguire il controllo dei caratteri. |
| **bool** [get_CloseInput](./get_closeinput/)() | Restituisce un valore che indica se lo stream sottostante o TextReader debba essere chiuso quando il lettore viene chiuso. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Restituisce il livello di conformità a cui aderirà il [XmlReader](../xmlreader/). |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Restituisce un valore che determina l'elaborazione dei DTD. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Restituisce un valore che indica se ignorare i commenti. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Restituisce un valore che indica se ignorare le istruzioni di elaborazione. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Restituisce un valore che indica se ignorare gli spazi bianchi insignificanti. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Restituisce lo spostamento del numero di riga dell'oggetto [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Restituisce lo spostamento della posizione di riga dell'oggetto [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Restituisce un valore che indica il numero massimo consentito di caratteri in un documento risultante dall'espansione delle entità. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Restituisce un valore che indica il numero massimo consentito di caratteri in un documento XML. Un valore zero (0) significa nessun limite sulla dimensione del documento XML. Un valore diverso da zero specifica la dimensione massima, in caratteri. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Restituisce il [XmlNameTable](../xmlnametable/) utilizzato per i confronti di stringhe atomizzate. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Restituisce un valore che indica se proibire l'elaborazione della definizione del tipo di documento (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Restituisce l'XmlSchemaSet da utilizzare durante la convalida dello schema. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Restituisce un valore che indica le impostazioni di convalida dello schema. Questa impostazione si applica agli oggetti [XmlReader](../xmlreader/) che convalidano schemi (il valore [XmlReaderSettings::get_ValidationType](./get_validationtype/) è [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Restituisce un valore che indica se il [XmlReader](../xmlreader/) eseguirà la convalida o l'assegnazione del tipo durante la lettura. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, inizializza semplicemente un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, inizializza semplicemente un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [Reset](./reset/)() | Ripristina i membri della classe delle impostazioni ai valori predefiniti. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Imposta un valore che indica se eseguire il controllo dei caratteri. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Imposta un valore che indica se lo stream sottostante o TextReader debba essere chiuso quando il lettore è chiuso. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Imposta il livello di conformità a cui aderirà il [XmlReader](../xmlreader/). |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Imposta un valore che determina l'elaborazione dei DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Imposta un valore che indica se ignorare i commenti. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Imposta un valore che indica se ignorare le istruzioni di elaborazione. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Imposta un valore che indica se ignorare gli spazi bianchi insignificanti. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Imposta lo spostamento del numero di riga dell'oggetto [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Imposta lo spostamento della posizione di riga dell'oggetto [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Imposta un valore che indica il numero massimo consentito di caratteri in un documento risultante dall'espansione delle entità. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Imposta un valore che indica il numero massimo consentito di caratteri in un documento XML. Un valore zero (0) significa nessun limite sulla dimensione del documento XML. Un valore diverso da zero specifica la dimensione massima, in caratteri. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Imposta il [XmlNameTable](../xmlnametable/) utilizzato per i confronti di stringhe atomizzate. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Imposta un valore che indica se proibire l'elaborazione della definizione del tipo di documento (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Imposta l'XmlSchemaSet da utilizzare durante la convalida dello schema. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Imposta un valore che indica le impostazioni di convalida dello schema. Questa impostazione si applica agli oggetti [XmlReader](../xmlreader/) che convalidano schemi (il valore [XmlReaderSettings::get_ValidationType](./get_validationtype/) è [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Imposta un valore che indica se il [XmlReader](../xmlreader/) eseguirà la convalida o l'assegnazione del tipo durante la lettura. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Imposta il [XmlResolver](../xmlresolver/) utilizzato per accedere a documenti esterni. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento di modello come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Aggiunge un gestore di eventi che si verifica quando il lettore incontra errori di convalida. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Rimuove un gestore di eventi che si verifica quando il lettore incontra errori di convalida. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Inizializza una nuova istanza della classe [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias per puntatore condiviso a un'istanza di questa classe. |

## Osservazioni

Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarla alle funzioni come argomento. 

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Xml](../)
* Libreria [Aspose.Slides](../../)