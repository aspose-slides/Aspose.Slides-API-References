---
title: XmlTextWriter
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un writer che fornisce un modo veloce, non memorizzato nella cache, solo in avanti per generare stream o file contenenti dati XML che conformano alle specifiche W3C Extensible Markup Language (XML) 1.0 e alle raccomandazioni Namespaces in XML.
type: docs
weight: 521
url: /it/system.xml/xmltextwriter/
---
## XmlTextWriter classe

Rappresenta un writer che fornisce un modo veloce, non memorizzato in cache, solo in avanti per generare stream o file contenenti dati XML conformi alle raccomandazioni W3C Extensible Markup Language (XML) 1.0 e Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Close](./close/)() override | Chiude questo stream e lo stream sottostante. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando il nome file specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando il nome file e l'oggetto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando lo stream specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando lo stream e l'oggetto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando il TextWriter specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando il TextWriter e gli oggetti [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando il [Text::StringBuilder](../../system.text/stringbuilder/) specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando gli oggetti [Text::StringBuilder](../../system.text/stringbuilder/) e [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando l'oggetto [XmlWriter](../xmlwriter/) specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nuova istanza di [XmlWriter](../xmlwriter/) utilizzando gli oggetti [XmlWriter](../xmlwriter/) e [XmlWriterSettings](../xmlwritersettings/) specificati. |
| void [Dispose](../xmlwriter/dispose/)() override | Rilascia tutte le risorse utilizzate dall'istanza corrente della classe [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali nonostante, secondo IEC 60559:1989, NaN non sia uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali nonostante, secondo IEC 60559:1989, NaN non sia uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| void [Flush](./flush/)() override | Svuota tutto ciò che è nel buffer verso gli stream sottostanti e svuota anche lo stream sottostante. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Restituisce l'oggetto stream sottostante. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Indica come è formattato l'output. |
| **int32_t** [get_Indentation](./get_indentation/)() | Restituisce il numero di IndentChars da scrivere per ogni livello nella gerarchia quando [XmlTextWriter::set_Formatting](./set_formatting/) è impostato a [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Restituisce quale carattere usare per l'indentazione quando [XmlTextWriter::set_Formatting](./set_formatting/) è impostato a [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Restituisce un valore che indica se abilitare il supporto dei namespace. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Restituisce quale carattere usare per racchiudere tra virgolette i valori degli attributi. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Restituisce l'oggetto [XmlWriterSettings](../xmlwritersettings/) usato per creare questa istanza [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Restituisce lo stato del writer. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Restituisce l'attuale ambito **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Restituisce un XmlSpace che rappresenta l'attuale ambito **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() della dichiarazione C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Restituisce il prefisso più vicino definito nell'attuale ambito del namespace per l'URI del namespace. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie per le subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie per le subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Indica come è formattato l'output. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Imposta quanti IndentChars scrivere per ogni livello nella gerarchia quando [XmlTextWriter::set_Formatting](./set_formatting/) è impostato a [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Imposta quale carattere usare per l'indentazione quando [XmlTextWriter::set_Formatting](./set_formatting/) è impostato a [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Imposta un valore che indica se abilitare il supporto dei namespace. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Imposta quale carattere usare per racchiudere tra virgolette i valori degli attributi. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei container alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando ridefinito in una classe derivata, scrive tutti gli attributi trovati nella posizione corrente del [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando ridefinito in una classe derivata, scrive un attributo con il nome locale, l'URI del namespace e il valore specificati. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando ridefinito in una classe derivata, scrive l'attributo con il nome locale e il valore specificati. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando ridefinito in una classe derivata, scrive l'attributo con il prefisso, il nome locale, l'URI del namespace e il valore specificati. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Codifica i byte binari specificati come base64 e scrive il testo risultante. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Codifica i byte binari specificati come binhex e scrive il testo risultante. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Scrive un blocco **...** contenente il testo specificato. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Forza la generazione di un'entità carattere per il valore Unicode specificato. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Scrive il testo un buffer alla volta. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Scrive un commento **** contenente il testo specificato. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Scrive la dichiarazione DOCTYPE con il nome specificato e gli attributi opzionali. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive un elemento con il nome locale e il valore specificati. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive un elemento con il nome locale, l'URI del namespace e il valore specificati. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive un elemento con il prefisso, il nome locale, l'URI del namespace e il valore specificati. |
| void [WriteEndAttribute](./writeendattribute/)() override | Chiude la chiamata [XmlTextWriter::WriteStartAttribute](./writestartattribute/) precedente. |
| void [WriteEndDocument](./writeenddocument/)() override | Chiude tutti gli elementi o attributi aperti e riporta il writer allo stato Start. |
| void [WriteEndElement](./writeendelement/)() override | Chiude un elemento e rimuove lo scope del namespace corrispondente. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Scrive un riferimento a entità come **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Chiude un elemento e rimuove lo scope del namespace corrispondente. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Scrive il nome specificato, assicurandosi che sia un nome valido secondo [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Scrive il nome specificato, assicurandosi che sia un **NmToken** valido secondo [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando ridefinito in una classe derivata, copia tutto dal reader al writer e sposta il reader all'inizio del fratello successivo. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copia tutto dall'oggetto XPathNavigator al writer. La posizione di XPathNavigator rimane invariata. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Scrive un'istruzione di elaborazione con uno spazio tra nome e testo come segue: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Scrive il nome qualificato per namespace. Questo metodo cerca il prefisso in scope per il namespace dato. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Scrive markup grezzo manualmente da un buffer di caratteri. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Scrive markup grezzo manualmente da una stringa. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Scrive l'inizio di un attributo. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive l'inizio di un attributo con il nome locale e l'URI del namespace specificati. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Scrive l'inizio di un attributo con il nome locale specificato. |
| void [WriteStartDocument](./writestartdocument/)() override | Scrive la dichiarazione XML con versione "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Scrive la dichiarazione XML con versione "1.0" e l'attributo standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Scrive il tag di apertura specificato e lo associa al namespace e al prefisso forniti. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando ridefinito in una classe derivata, scrive il tag di apertura specificato e lo associa al namespace fornito. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Quando ridefinito in una classe derivata, scrive un tag di apertura con il nome locale specificato. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Scrive il contenuto testuale fornito. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Genera e scrive l'entità carattere surrogate per la coppia di caratteri surrogate. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Scrive il valore dell'oggetto. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Scrive un valore [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Scrive un valore [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Scrive un valore [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Scrive un valore [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Scrive un valore [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Scrive un numero in virgola mobile a precisione singola. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Scrive un valore [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Scrive un valore [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Scrive un valore [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Scrive lo spazio bianco fornito. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Crea un'istanza della classe [XmlTextWriter](./) usando lo stream e la codifica specificati. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Crea un'istanza della classe [XmlTextWriter](./) usando il file specificato. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crea un'istanza della classe [XmlTextWriter](./) usando il TextWriter specificato. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | Un alias per un puntatore condiviso a un'istanza di questa classe. |

## Note

Si consiglia di utilizzare invece la classe [XmlWriter](../xmlwriter/).

Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

## Vedi anche

* Classe [XmlWriter](../xmlwriter/)
* Namespace [System::Xml](../)
* Libreria [Aspose.Slides](../../)