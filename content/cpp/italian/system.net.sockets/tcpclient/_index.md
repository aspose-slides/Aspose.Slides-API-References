---
title: TcpClient
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un client per i servizi di rete TCP. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 66
url: /it/system.net.sockets/tcpclient/
---
## TcpClient classe

Rappresenta un client per i servizi di rete TCP. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
class TcpClient : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di connessione asincrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di connessione asincrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di connessione asincrona. |
| void [Close](./close/)() | Chiude la connessione e rilascia l'istanza corrente. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Stabilisce una connessione all'host remoto specificato. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Stabilisce una connessione all'host remoto specificato. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Stabilisce una connessione all'host remoto specificato. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Stabilisce una connessione all'host remoto specificato. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Non fa nulla. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Attende finché l'operazione di connessione asincrona specificata non termina. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per usi interni. |
| **int32_t** [get_Available](./get_available/)() | Restituisce il numero di byte ricevuti e pronti per la lettura. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Ottiene il socket. |
| **bool** [get_Connected](./get_connected/)() | Restituisce un valore che indica se il socket è connesso all'host remoto. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Ottiene un valore che indica se l'istanza corrente consente a un solo client di utilizzare una porta. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Ottiene un valore che indica se il socket ritarderà la chiusura nel tentativo di inviare tutti i dati in sospeso. |
| **bool** [get_NoDelay](./get_nodelay/)() | Ottiene un valore che indica se l'istanza corrente utilizza l'algoritmo di Nagle. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Ottiene la dimensione del buffer usato per la ricezione dei dati. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Ottiene un valore che indica il periodo di tempo dopo il quale il ricevimento dei dati scadrà. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Ottiene la dimensione del buffer usato per l'invio dei dati. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Ottiene un valore che indica il periodo di tempo dopo il quale l'invio dei dati scadrà. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Restituisce lo stream usato per l'invio e la ricezione dei dati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Costruisce una nuova istanza. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la copia della costruzione delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la copia della costruzione delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Imposta il socket. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Imposta un valore che indica se l'istanza corrente consente a un solo client di utilizzare una porta. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Imposta un valore che indica se il socket ritarderà la chiusura nel tentativo di inviare tutti i dati in sospeso. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Imposta un valore che indica se l'istanza corrente utilizza l'algoritmo di Nagle. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Imposta la dimensione del buffer usato per la ricezione dei dati. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Imposta un valore che indica il periodo di tempo dopo il quale il ricevimento dei dati scadrà. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Imposta la dimensione del buffer usato per l'invio dei dati. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Imposta un valore che indica il periodo di tempo dopo il quale l'invio dei dati scadrà. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Costruisce una nuova istanza. |
|  [TcpClient](./tcpclient/)() | Costruisce una nuova istanza. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Costruisce una nuova istanza. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Costruisce una nuova istanza. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente di convertire oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
| virtual  [~TcpClient](./~tcpclient/)() | Distrugge l'istanza corrente. |

## Vedi anche

* Classe [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Libreria [Aspose.Slides](../../)