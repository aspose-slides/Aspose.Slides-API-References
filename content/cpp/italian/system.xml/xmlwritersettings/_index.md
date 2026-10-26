---
title: XmlWriterSettings
second_title: Riferimento API Aspose.Slides per C++
description: "Specifica un insieme di funzionalità da supportare sull'oggetto XmlWriter creato dal metodo XmlWriter::Create."
type: docs
weight: 586
url: /it/system.xml/xmlwritersettings/
---
## XmlWriterSettings classe


Specifica un insieme di funzionalità da supportare sull'oggetto [XmlWriter](../xmlwriter/) creato dal metodo [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Crea una copia dell'istanza [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Restituisce un valore che indica se lo scrittore XML deve verificare che tutti i caratteri nel documento siano conformi alla sezione "2.2 Characters" del W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Restituisce un valore che indica se il [XmlWriter](../xmlwriter/) deve anche chiudere lo stream sottostante o TextWriter quando viene chiamato il metodo [XmlWriter::Close](../xmlwriter/close/). |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Restituisce il livello di conformità che lo scrittore XML verifica nell'output XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Restituisce un valore che indica se il [XmlWriter](../xmlwriter/) non esegue l'escape degli attributi URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Restituisce il tipo di codifica del testo da usare. |
| **bool** [get_Indent](./get_indent/)() | Restituisce un valore che indica se indentare gli elementi. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Restituisce la stringa di caratteri da usare per l'indentazione. Questa impostazione è usata quando il valore [XmlWriterSettings::set_Indent](./set_indent/) è impostato su **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Restituisce un valore che indica se il [XmlWriter](../xmlwriter/) deve rimuovere le dichiarazioni di namespace duplicate durante la scrittura del contenuto XML. Il comportamento predefinito è che lo scrittore emetta tutte le dichiarazioni di namespace presenti nel risolutore di namespace dello scrittore. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Restituisce la stringa di caratteri da usare per le interruzioni di riga. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Restituisce un valore che indica se normalizzare le interruzioni di riga nell'output. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Restituisce un valore che indica se scrivere gli attributi su una nuova riga. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Restituisce un valore che indica se omettere una dichiarazione XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Restituisce il metodo usato per serializzare l'output [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Restituisce un valore che indica se il [XmlWriter](../xmlwriter/) aggiungerà i tag di chiusura a tutti i tag di elemento non chiusi quando viene chiamato il metodo [XmlWriter::Close](../xmlwriter/close/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la costruzione copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la costruzione copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [Reset](./reset/)() | Reimposta i membri della classe delle impostazioni ai valori predefiniti. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Imposta un valore che indica se lo scrittore XML deve verificare che tutti i caratteri nel documento siano conformi alla sezione "2.2 Characters" del W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Imposta un valore che indica se il [XmlWriter](../xmlwriter/) deve anche chiudere lo stream sottostante o TextWriter quando viene chiamato il metodo [XmlWriter::Close](../xmlwriter/close/). |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Imposta il livello di conformità che lo scrittore XML verifica nell'output XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Imposta un valore che indica se il [XmlWriter](../xmlwriter/) non esegue l'escape degli attributi URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Imposta il tipo di codifica del testo da usare. |
| void [set_Indent](./set_indent/)(**bool**) | Imposta un valore che indica se indentare gli elementi. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Imposta la stringa di caratteri da usare per l'indentazione. Questa impostazione è usata quando il valore [XmlWriterSettings::set_Indent](./set_indent/) è impostato su **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Imposta un valore che indica se il [XmlWriter](../xmlwriter/) deve rimuovere le dichiarazioni di namespace duplicate durante la scrittura del contenuto XML. Il comportamento predefinito è che lo scrittore emetta tutte le dichiarazioni di namespace presenti nel risolutore di namespace dello scrittore. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Imposta la stringa di caratteri da usare per le interruzioni di riga. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Imposta un valore che indica se normalizzare le interruzioni di riga nell'output. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Imposta un valore che indica se scrivere gli attributi su una nuova riga. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Imposta un valore che indica se omettere una dichiarazione XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Imposta un valore che indica se il [XmlWriter](../xmlwriter/) aggiungerà i tag di chiusura a tutti i tag di elemento non chiusi quando viene chiamato il metodo [XmlWriter::Close](../xmlwriter/close/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un weak pointer (piuttosto che shared). Consente di passare i puntatori in contenitori alla modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Inizializza una nuova istanza della classe [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | Un alias per shared pointer a un'istanza di questa classe. |

## Osservazioni

Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché causerebbe errori di runtime e/o violazioni di assert. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare tale puntatore per passarla alle funzioni come argomento. 

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [System::Xml](../)
* Libreria [Aspose.Slides](../../)