---
title: BinaryReader
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un lettore che legge tipi di dati primitivi come dati binari in una codifica specifica. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 92
url: /it/system.io/binaryreader/
---
## BinaryReader classe

Rappresenta un lettore che legge tipi di dati primitivi come dati binari in una codifica specifica. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocerebbe errori di runtime e/o interruzioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
class BinaryReader : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Costruisce un'istanza della classe [BinaryReader](./) che legge i dati dallo stream specificato usando la codifica UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Costruisce un'istanza della classe [BinaryReader](./) che legge i dati dallo stream specificato usando la codifica specificata. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Costruisce un'istanza della classe [BinaryReader](./) che legge i dati dallo stream specificato usando la codifica specificata. |
| virtual void [Close](./close/)() | Chiude l'oggetto [BinaryReader](./) corrente e lo stream di input sottostante. |
| void [Dispose](./dispose/)() override | Rilascia tutte le risorse usate dall'oggetto corrente e chiude lo stream sottostante. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Restituisce lo stream di input. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, si limita a inizializzare un nuovo oggetto e consente la copia nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, si limita a inizializzare un nuovo oggetto e consente la copia nelle sottoclassi. |
| virtual int [PeekChar](./peekchar/)() | Legge un singolo carattere dallo stream di input senza modificare il cursore di lettura dello stream. |
| virtual int [Read](./read/)() | Legge un singolo carattere dallo stream di input. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Legge il numero specificato di byte dallo stream di input e li scrive nell'array di byte specificato. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Legge il numero specificato di caratteri dallo stream di input, li converte in codifica UTF-16 e scrive i caratteri UTF-16 risultanti nell'array di caratteri specificato a partire dalla posizione indicata. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Legge un singolo byte dallo stream di input e restituisce la sua rappresentazione booleana. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Legge un singolo byte dallo stream di input. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Legge il numero specificato di byte dallo stream di input. |
| virtual char_t [ReadChar](./readchar/)() | Legge un singolo carattere dallo stream di input. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Legge il numero specificato di caratteri dallo stream di input e li restituisce in codifica UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NON IMPLEMENTATO. |
| virtual **double** [ReadDouble](./readdouble/)() | Legge 8 byte dallo stream di input e li restituisce come valore in virgola mobile a doppia precisione. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Legge 2 byte dallo stream di input e li restituisce come valore intero a 16 bit. |
| virtual int [ReadInt32](./readint32/)() | Legge 4 byte dallo stream di input e li restituisce come valore intero a 32 bit. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Legge 8 byte dallo stream di input e li restituisce come valore intero a 64 bit. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Legge un singolo byte dallo stream di input e lo restituisce come valore intero a 8 bit con segno. |
| virtual **float** [ReadSingle](./readsingle/)() | Legge 4 byte dallo stream di input e li restituisce come valore in virgola mobile a precisione singola. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Legge una stringa dallo stream corrente. La stringa è preceduta dalla lunghezza, codificata come intero a 7 bit per volta. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Legge 2 byte dallo stream di input e li restituisce come valore intero senza segno a 16 bit. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Legge 4 byte dallo stream di input e li restituisce come valore intero senza segno a 32 bit. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Legge 8 byte dallo stream di input e li restituisce come valore intero senza segno a 64 bit. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n-esimo a un puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IDisposable](../../system/idisposable/)
* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)