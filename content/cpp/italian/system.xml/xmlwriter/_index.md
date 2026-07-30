---
title: XmlWriter
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un writer che fornisce un modo veloce, non memorizzato in cache e solo in avanti per generare stream o file che contengono dati XML.
type: docs
weight: 573
url: /it/system.xml/xmlwriter/
---
## XmlWriter classe

Rappresenta un writer che fornisce un modo veloce, non memorizzato in cache e solo in avanti per generare stream o file che contengono dati XML.

```cpp
class XmlWriter : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Close](./close/)() | Quando sovrascritto in una classe derivata, chiude questo stream e lo stream sottostante. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Crea una nuova istanza [XmlWriter](./) usando il nome file specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza [XmlWriter](./) usando il nome file e l'oggetto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crea una nuova istanza [XmlWriter](./) usando lo stream specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza [XmlWriter](./) usando lo stream e l'oggetto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crea una nuova istanza [XmlWriter](./) usando il TextWriter specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza [XmlWriter](./) usando il TextWriter e gli oggetti [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Crea una nuova istanza [XmlWriter](./) usando il [Text::StringBuilder](../../system.text/stringbuilder/) specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza [XmlWriter](./) usando gli oggetti [Text::StringBuilder](../../system.text/stringbuilder/) e [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Crea una nuova istanza [XmlWriter](./) usando l'oggetto [XmlWriter](./) specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza [XmlWriter](./) usando gli oggetti [XmlWriter](./) e [XmlWriterSettings](../xmlwritersettings/) specificati. |
| void [Dispose](./dispose/)() override | Rilascia tutte le risorse usate dall'istanza corrente della classe [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual void [Flush](./flush/)() | Quando sovrascritto in una classe derivata, svuota il buffer verso gli stream sottostanti e svuota anche lo stream sottostante. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Restituisce l'oggetto [XmlWriterSettings](../xmlwritersettings/) usato per creare questa istanza [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Quando sovrascritto in una classe derivata, ottiene lo stato del writer. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Quando sovrascritto in una classe derivata, ottiene l'ambito corrente **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Quando sovrascritto in una classe derivata, ottiene un XmlSpace che rappresenta l'ambito corrente **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Quando sovrascritto in una classe derivata, restituisce il prefisso più vicino definito nell'ambito del namespace corrente per l'URI del namespace. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia niente, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie nelle sotto-classi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia niente, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie nelle sotto-classi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il conteggio di riferimento condiviso del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore attuale del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il conteggio di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il conteggio di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco (unlock) dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il conteggio di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il conteggio di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando sovrascritto in una classe derivata, scrive tutti gli attributi trovati nella posizione corrente di [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive un attributo con il nome locale, l'URI del namespace e il valore specificati. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive l'attributo con il nome locale e il valore specificati. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive l'attributo con il prefisso, il nome locale, l'URI del namespace e il valore specificati. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Quando sovrascritto in una classe derivata, codifica i byte binari specificati come Base64 e scrive il testo risultante. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Quando sovrascritto in una classe derivata, codifica i byte binari specificati come **BinHex** e scrive il testo risultante. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Quando sovrascritto in una classe derivata, scrive un blocco **...** contenente il testo specificato. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Quando sovrascritto in una classe derivata, forza la generazione di un'entità carattere per il valore Unicode del carattere specificato. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Quando sovrascritto in una classe derivata, scrive testo un buffer alla volta. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Quando sovrascritto in una classe derivata, scrive un commento **** contenente il testo specificato. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive la dichiarazione DOCTYPE con il nome specificato e gli attributi opzionali. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive un elemento con il nome locale e il valore specificati. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive un elemento con il nome locale, l'URI del namespace e il valore specificati. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive un elemento con il prefisso, il nome locale, l'URI del namespace e il valore specificati. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Quando sovrascritto in una classe derivata, chiude la chiamata precedente XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Quando sovrascritto in una classe derivata, chiude tutti gli elementi o attributi aperti e riporta il writer nello stato Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Quando sovrascritto in una classe derivata, chiude un elemento e rimuove lo scope del namespace corrispondente. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive un riferimento a entità come **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Quando sovrascritto in una classe derivata, chiude un elemento e rimuove lo scope del namespace corrispondente. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive il nome specificato, assicurandosi che sia un nome valido secondo la raccomandazione W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive il nome specificato, assicurandosi che sia un NmToken valido secondo la raccomandazione W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando sovrascritto in una classe derivata, copia tutto dal reader al writer e sposta il reader all'inizio del fratello successivo. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copia tutto dall'oggetto XPathNavigator al writer. La posizione di XPathNavigator rimane invariata. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Quando sovrascritto in una classe derivata, scrive un'istruzione di processing con uno spazio tra nome e testo, così: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive il nome qualificato per namespace. Questo metodo ricerca il prefisso disponibile per il namespace fornito. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Quando sovrascritto in una classe derivata, scrive markup grezzo manualmente da un buffer di caratteri. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive markup grezzo manualmente da una stringa. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive l'inizio di un attributo con il nome locale e l'URI del namespace specificati. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive l'inizio di un attributo con il prefisso, il nome locale e l'URI del namespace specificati. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Scrive l'inizio di un attributo con il nome locale specificato. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Quando sovrascritto in una classe derivata, scrive la dichiarazione XML con la versione "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Quando sovrascritto in una classe derivata, scrive la dichiarazione XML con la versione "1.0" e l'attributo standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive il tag di apertura specificato e lo associa al namespace fornito. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive il tag di apertura specificato e lo associa al namespace e al prefisso forniti. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive un tag di apertura con il nome locale specificato. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Quando sovrascritto in una classe derivata, scrive il contenuto di testo fornito. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Quando sovrascritto in una classe derivata, genera e scrive l'entità carattere surrogata per la coppia di caratteri surrogata. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Scrive il valore dell'oggetto. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Scrive un valore [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Scrive un valore [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Scrive un valore [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Scrive un valore [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Scrive un valore [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Scrive un numero in virgola mobile a precisione singola. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Scrive un valore [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Scrive un valore [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Scrive un valore [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Quando sovrascritto in una classe derivata, scrive lo spazio bianco fornito. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | Un alias per shared pointer a un'istanza di questa classe. |

## Vedi anche

* Classe [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Libreria [Aspose.Slides](../../)