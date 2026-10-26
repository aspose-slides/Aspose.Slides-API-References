---
title: MemoryStream
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un flusso che legge e scrive dalla memoria. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 326
url: /it/system.io/memorystream/
---
## classe MemoryStream

Rappresenta un flusso che legge e scrive nella memoria. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherebbe errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class MemoryStream : public System::IO::Stream
```

## Metodi

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Avvia un'operazione di lettura asincrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Avvia un'operazione di scrittura asincrona. |
| void [Close](./close/)() override | Chiude il flusso. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Copia i byte nel flusso specificato. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Copia i byte nel flusso specificato, usando la dimensione del buffer specificata. |
| void [Dispose](../stream/dispose/)() override | Rilascia tutte le risorse usate dall'oggetto corrente e chiude il flusso. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Attende finché l'operazione di lettura asincrona specificata non è completata. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Termina un'operazione di scrittura asincrona. Attende finché l'operazione di scrittura asincrona specificata non è completata. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, compreso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, compreso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| void [Flush](./flush/)() override | Non fa nulla. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Cancella in modo asincrono tutti i buffer per questo flusso, fa sì che tutti i dati memorizzati vengano scritti sul dispositivo sottostante e monitora le richieste di annullamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Cancella in modo asincrono tutti i buffer per questo flusso, fa sì che tutti i dati memorizzati vengano scritti sul dispositivo sottostante e monitora le richieste di annullamento. |
| **bool** [get_CanRead](./get_canread/)() const override | Determina se il flusso è leggibile. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determina se il flusso supporta il posizionamento. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Ottiene un valore che determina se il flusso corrente può scadere. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determina se il flusso è scrivibile. |
| int [get_Capacity](./get_capacity/)() | Restituisce la capacità corrente del buffer di memoria sottostante. |
| **int64_t** [get_Length](./get_length/)() const override | Restituisce la lunghezza del flusso in byte. |
| **int64_t** [get_Position](./get_position/)() const override | Restituisce la posizione corrente del flusso. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Ottiene un valore, in millisecondi, che determina per quanto tempo il flusso proverà a leggere prima di scadere. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Ottiene un valore, in millisecondi, che determina per quanto tempo il flusso proverà a scrivere prima di scadere. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | Restituisce un puntatore al buffer sottostante. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [MemoryStream](./memorystream/)() | Costruisce una nuova istanza della classe [MemoryStream](./) con capacità iniziale pari a 0. |
|  [MemoryStream](./memorystream/)(int) | Costruisce una nuova istanza della classe [MemoryStream](./) che rappresenta un flusso basato su un buffer di memoria della dimensione specificata. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Costruisce una nuova istanza della classe [MemoryStream](./) che rappresenta un flusso di memoria collegato al buffer di memoria specificato. Un parametro specifica se il flusso è scrivibile. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | Costruisce una nuova istanza della classe [MemoryStream](./) che rappresenta un flusso di memoria collegato a un segmento del buffer di memoria specificato a partire dall'indice specificato e includendo il numero specificato di elementi. I parametri specificano se il flusso è scrivibile e se il metodo GetBytes() può essere chiamato. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, realmente, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, realmente, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Legge il numero specificato di byte dal flusso e li scrive nello span di byte specificato. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Legge in modo asincrono una sequenza di byte dal flusso corrente, avanza la posizione all'interno del flusso del numero di byte letti e monitora le richieste di annullamento. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Legge in modo asincrono una sequenza di byte dal flusso corrente, avanza la posizione all'interno del flusso del numero di byte letti e monitora le richieste di annullamento. |
| int [ReadByte](./readbyte/)() override | Legge un singolo byte dal flusso e restituisce un valore intero a 32 bit equivalente al valore del byte letto. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Imposta la posizione del flusso rappresentato dall'oggetto corrente. |
| void [set_Capacity](./set_capacity/)(int) | Imposta la capacità del buffer di memoria sottostante. |
| void [set_Position](./set_position/)(**int64_t**) override | Imposta la posizione del flusso. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Imposta un valore che determina se il flusso corrente può scadere. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Imposta un valore, in millisecondi, che determina per quanto tempo il flusso proverà a leggere prima di scadere. |
| void [SetLength](./setlength/)(**int64_t**) override | Imposta la lunghezza del flusso rappresentato dall'oggetto corrente. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | Restituisce una copia del buffer di memoria sottostante come array di byte. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | Restituisce l'array di byte senza segno da cui è stato creato questo flusso. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Scrive l'intervallo specificato di byte dallo span di byte specificato al flusso. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Scrive in modo asincrono una sequenza di byte al flusso corrente, avanza la posizione corrente all'interno di questo flusso del numero di byte scritti e monitora le richieste di annullamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Scrive in modo asincrono una sequenza di byte al flusso corrente, avanza la posizione corrente all'interno di questo flusso del numero di byte scritti e monitora le richieste di annullamento. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Scrive il valore intero senza segno a 8 bit specificato al flusso. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | Scrive il contenuto del buffer sottostante nel flusso specificato. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | Un flusso senza memorizzazione sottostante. |

## Definizioni di tipo

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias per un puntatore condiviso a se stesso. |

## Vedi anche

* Classe [Stream](../stream/)
* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)