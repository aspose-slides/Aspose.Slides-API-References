---
title: BasicSTDIOStreamWrapper
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un wrapper simile a System.IO.Stream per std::basic_iostream e i suoi oggetti derivati. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare tale puntatore per passarla alle funzioni come argomento."
type: docs
weight: 1
url: /it/system.io/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper classe

Rappresenta un wrapper in stile [System.IO.Stream](../stream/) per std::basic_iostream e i suoi oggetti derivati. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherebbe errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare tale puntatore per passarla alle funzioni come argomento.

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../stdiostreampositionpreference/)) | Crea una nuova istanza di [BasicSTDIOStreamWrapper](./). |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const [BasicSTDIOStreamWrapper](./)\&) | Costruttore di copia. Eliminato. |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Crea una nuova istanza di [BasicSTDIStreamWrapper](../basicstdistreamwrapper/). |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | Costruttore di copia. Eliminato. |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Crea una nuova istanza di [BasicSTDOStreamWrapper](../basicstdostreamwrapper/). |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | Costruttore di copia. Eliminato. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inizia un'operazione di lettura asincrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inizia un'operazione di scrittura asincrona. |
| virtual void [Close](../stream/close/)() | Chiude lo stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Copia byte nello stream specificato. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Copia byte nello stream specificato, usando la dimensione di buffer specificata. |
| void [Dispose](../stream/dispose/)() override | Rilascia tutte le risorse usate dall'oggetto corrente e chiude lo stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Attende fino al completamento dell'operazione di lettura asincrona specificata. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Termina un'operazione di scrittura asincrona. Attende fino al completamento dell'operazione di scrittura asincrona specificata. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| void [Flush](./flush/)() override | Svuota i buffer di questo stream e scrive tutti i dati bufferizzati nello storage sottostante. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Cancella in modo asincrono tutti i buffer di questo stream, fa sì che i dati bufferizzati vengano scritti sul dispositivo sottostante e monitora le richieste di annullamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Cancella in modo asincrono tutti i buffer di questo stream, fa sì che i dati bufferizzati vengano scritti sul dispositivo sottostante e monitora le richieste di annullamento. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Determina se lo stream supporta il posizionamento. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Ottiene un valore che determina se lo stream corrente può scadere. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Determina se lo stream supporta la scrittura. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Restituisce la lunghezza dello stream. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Restituisce la posizione corrente dello stream. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Ottiene un valore, in millisecondi, che determina per quanto tempo lo stream tenterà di leggere prima di scadere. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Ottiene un valore, in millisecondi, che determina per quanto tempo lo stream tenterà di scrivere prima di scadere. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [BasicSTDIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIOStreamWrapper](./)\&) | Operatore di assegnazione copia. Eliminato. |
| [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\& [operator=](../basicstdistreamwrapper/operator_equal/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | Operatore di assegnazione copia. Eliminato. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Operatore di assegnazione copia. Eliminato. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\& [operator=](../basicstdostreamwrapper/operator_equal/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | Operatore di assegnazione copia. Eliminato. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Se la modalità di wrapping è binaria, legge il numero specificato di byte dallo stream, altrimenti legge il numero specificato di caratteri e li converte al tipo **uint8_t**. Scrive il risultato della lettura nell'array di byte specificato. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Legge il numero specificato di byte dallo stream e li scrive nello span di byte specificato. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Legge in modo asincrono una sequenza di byte dallo stream corrente, avanza la posizione nello stream del numero di byte letti e monitora le richieste di annullamento. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Legge in modo asincrono una sequenza di byte dallo stream corrente, avanza la posizione nello stream del numero di byte letti e monitora le richieste di annullamento. |
| int [ReadByte](./readbyte/)() override | Se la modalità di wrapping è binaria, legge un singolo byte dall'ultimo buffer di caratteri decodificati, altrimenti legge un singolo carattere dallo stream e lo converte al tipo **uint8_t**. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | Informazioni RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Imposta la posizione dello stream rappresentato dall'oggetto corrente. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Imposta la posizione dello stream. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Imposta un valore che determina se lo stream corrente può scadere. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Imposta un valore, in millisecondi, che determina per quanto tempo lo stream tenterà di leggere prima di scadere. |
| void [SetLength](./setlength/)(**int64_t**) override | Imposta la lunghezza dello stream rappresentato dall'oggetto corrente. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Costruttore di copia. Eliminato. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Se la modalità di wrapping è binaria, scrive nello stream il sottointervallo di byte specificato dall'array di byte specificato, altrimenti converte il sottointervallo di byte specificato dall'array di byte al tipo char_type e quindi scrive il risultato nello stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Scrive il sottointervallo di byte specificato dall'array di byte nello stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Scrive il sottointervallo di byte specificato dall'array di byte nello stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Scrive il sottointervallo di byte specificato dallo span di byte nello stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Scrive in modo asincrono una sequenza di byte nello stream corrente, avanza la posizione corrente nello stream del numero di byte scritti e monitora le richieste di annullamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Scrive in modo asincrono una sequenza di byte nello stream corrente, avanza la posizione corrente nello stream del numero di byte scritti e monitora le richieste di annullamento. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Se la modalità di wrapping è binaria, scrive nello stream il valore intero unsigned a 8 bit specificato, altrimenti lo converte al tipo char_type e quindi scrive il risultato nello stream. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Null](../stream/null/) | Uno stream senza storage sottostante. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Vedi anche

* Classe [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* Classe [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)