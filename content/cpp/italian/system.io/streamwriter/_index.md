---
title: StreamWriter
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un writer che scrive caratteri su un flusso di byte. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 391
url: /it/system.io/streamwriter/
---
## StreamWriter classe

Rappresenta un writer che scrive caratteri su un flusso di byte. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Close](./close/)() override | Chiude lo stream e rilascia le risorse acquisite. |
| void [Dispose](./dispose/)() override | Rilascia tutte le risorse utilizzate dall'oggetto corrente e chiude lo stream sottostante. |
| virtual void [Dispose](./dispose/)(**bool**) | Rilascia tutte le risorse utilizzate dall'oggetto corrente e chiude lo stream sottostante. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| void [Flush](./flush/)() override | Svuota il contenuto del buffer nello stream sottostante e poi svuota lo stream sottostante. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Restituisce un valore che indica se il [StreamWriter](./) eseguirà il flush dei dati sullo stream sottostante ogni volta che viene chiamato il metodo [StreamWriter::Write](./write/). |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Restituisce un puntatore condiviso a un oggetto che rappresenta lo stream sottostante. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Restituisce la codifica attualmente utilizzata. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Restituisce l'oggetto [IFormatProvider](../../system/iformatprovider/) attualmente utilizzato. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Restituisce l'oggetto [IFormatProvider](../../system/iformatprovider/) attualmente utilizzato. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Restituisce una stringa di terminatore di riga. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Restituisce una stringa di terminatore di riga. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia realmente nulla, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Restituisce un valore che specifica se il [StreamWriter](./) deve eseguire il flush dei dati sullo stream sottostante ogni volta che il metodo [StreamWriter::Write](./write/) è chiamato. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Imposta una stringa di terminatore di riga. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Costruisce un'istanza dell'oggetto [StreamWriter](./) che scrive caratteri sullo stream sottostante specificato usando la codifica UTF-8 e un buffer di dimensione predefinita di 1024 byte. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Costruisce un'istanza dell'oggetto [StreamWriter](./) che scrive caratteri sullo stream sottostante specificato usando la codifica specificata e un buffer di dimensione predefinita di 1024 byte. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Costruisce un'istanza dell'oggetto [StreamWriter](./) che scrive caratteri sullo stream sottostante specificato usando la codifica specificata e un buffer delle dimensioni specificate. Un parametro specifica se lo stream sottostante debba essere chiuso quando l'oggetto [StreamWriter](./) è eliminato. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Costruisce un'istanza dell'oggetto [StreamWriter](./) che scrive caratteri nel file specificato usando la codifica UTF-8 e un buffer di dimensione predefinita di 1024 byte. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Costruisce un'istanza dell'oggetto [StreamWriter](./) che scrive caratteri nel file specificato usando la codifica specificata e un buffer di dimensione predefinita di 1024 byte. Un parametro specifica se i dati devono essere aggiunti al file o il file deve essere sovrascritto. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Costruisce un'istanza dell'oggetto [StreamWriter](./) che scrive caratteri nel file specificato usando la codifica specificata e la dimensione del buffer. Un parametro specifica se i dati devono essere aggiunti al file o il file deve essere sovrascritto. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [Write](./write/)(char_t) override | Scrive il carattere specificato nello stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Scrive la stringa specificata nello stream. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Scrive la rappresentazione in stringa dell'oggetto specificato nello stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Scrive tutti i caratteri dall'array specificato nello stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Scrive l'intervallo specificato di caratteri UTF-16 dall'array di caratteri specificato nello stream. |
| void [Write](./write/)(const char_t *) override | Scrive la c-string specificata nello stream. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Scrive la rappresentazione in stringa dell'oggetto specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Scrive la rappresentazione in stringa del valore booleano specificato nello stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Scrive la rappresentazione in stringa dell'oggetto [Decimal](../../system/decimal/) specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Scrive la rappresentazione in stringa del valore a doppia precisione specificato nello stream. |
| virtual void [Write](../textwriter/write/)(int) | Scrive la rappresentazione in stringa del valore intero a 32 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Scrive la rappresentazione in stringa del valore intero a 64 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Scrive la rappresentazione in stringa del valore a precisione singola specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Scrive la rappresentazione in stringa del valore intero senza segno a 32 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Scrive la rappresentazione in stringa del valore intero senza segno a 64 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Scrive la rappresentazione in stringa dell'oggetto [TypeInfo](../../system/typeinfo/) specificato nello stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato nello stream. |
| void [WriteLine](./writeline/)() override | Scrive i caratteri di terminatore di riga nello stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Scrive la stringa specificata seguita dai caratteri di terminazione di riga nello stream. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Scrive la rappresentazione in stringa dell'oggetto specificato seguita dai caratteri di terminazione di riga nello stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Scrive tutti i caratteri dall'array specificato seguiti dai caratteri di terminazione di riga nello stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Scrive l'intervallo specificato di caratteri UTF-16 dall'array di caratteri specificato, seguito dai caratteri di terminazione di riga nello stream. |
| void [WriteLine](./writeline/)(const char_t *) override | Scrive la c-string specificata seguita dai caratteri di terminazione di riga nello stream. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Scrive la rappresentazione in stringa dell'oggetto specificato seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Scrive la rappresentazione in stringa del valore booleano specificato, seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Scrive il carattere specificato seguito dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Scrive la rappresentazione in stringa dell'oggetto [Decimal](../../system/decimal/) specificato seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Scrive la rappresentazione in stringa del valore a doppia precisione specificato, seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Scrive la rappresentazione in stringa del valore intero a 32 bit specificato, seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Scrive la rappresentazione in stringa del valore intero a 64 bit specificato, seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Scrive la rappresentazione in stringa del valore a precisione singola specificato, seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Scrive la rappresentazione in stringa del valore intero senza segno a 32 bit specificato, seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Scrive la rappresentazione in stringa del valore intero senza segno a 64 bit specificato, seguita dai caratteri di terminazione di riga nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Scrive la rappresentazione in stringa dell'oggetto [TypeInfo](../../system/typeinfo/) specificato, seguita dai caratteri di terminazione di riga nello stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato, seguiti dai caratteri di terminazione di riga nello stream. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
|  [~StreamWriter](./~streamwriter/)() | Distruttore. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Distruttore. |

## Vedi anche

* Classe [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Libreria [Aspose.Slides](../../)