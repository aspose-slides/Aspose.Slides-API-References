---
title: ServicePointManager
second_title: Aspose.Slides per C++ Riferimento API
description: "Gestisce le fasi del ciclo di vita (creazione, manutenzione e eliminazione) delle istanze della classe ServicePoint. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare tale puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 430
url: /it/system.net/servicepointmanager/
---
## ServicePointManager classe

Gestisce le fasi del ciclo di vita (creazione, mantenimento ed eliminazione) delle istanze della classe [ServicePoint](../servicepoint/). Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento.

```cpp
class ServicePointManager : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Ottiene una politica di certificato. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Ottiene un valore che indica se il certificato deve essere verificato rispetto all'elenco di revoca delle autorità di certificazione. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Ottiene il numero massimo di connessioni concorrenti consentite dalle istanze della classe ServicePoint. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Ottiene un timeout in millisecondi durante il quale una risoluzione DNS è considerata valida. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Ottiene un valore che indica se una risoluzione DNS ruota tra gli indirizzi IP applicabili. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Restituisce la politica di crittografia utilizzata dall'istanza corrente. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Ottiene un valore che indica se le istanze della classe ServicePoint usano il comportamento 100-Continue. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Ottiene il tempo di inattività massimo delle istanze della classe ServicePoint. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Ottiene il numero massimo di istanze della classe ServicePoint che possono essere gestite dall'istanza corrente. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Ottiene un valore che indica se i socket delle connessioni in uscita usano l'opzione 'SO_REUSE_UNICASTPORT'. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Ottiene il tipo di protocollo di sicurezza usato dalle istanze della classe ServicePoint gestite dall'istanza corrente. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Ottiene la callback usata per convalidare un certificato server. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Ottiene un valore che indica se le istanze della classe ServicePoint usano l'algoritmo di Nagle. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e abilita la costruzione copia di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e abilita la costruzione copia di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso di un valore specificato. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Imposta una politica di certificato. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Imposta un valore che indica se il certificato deve essere verificato rispetto all'elenco di revoca dell'autorità di certificazione. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Imposta il numero massimo di connessioni concorrenti consentite dalle istanze della classe ServicePoint. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Imposta un timeout in millisecondi durante il quale una risoluzione DNS è considerata valida. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Imposta un valore che indica se una risoluzione DNS ruota tra gli indirizzi IP applicabili. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Imposta un valore che indica se le istanze della classe ServicePoint usano il comportamento 100-Continue. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Imposta il tempo di inattività massimo delle istanze della classe ServicePoint. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Imposta il numero massimo di istanze della classe ServicePoint che possono essere gestite dall'istanza corrente. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Imposta un valore che indica se i socket delle connessioni in uscita usano l'opzione 'SO_REUSE_UNICASTPORT'. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Imposta il tipo di protocollo di sicurezza usato dalle istanze della classe ServicePoint gestite dall'istanza corrente. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Imposta la callback usata per convalidare un certificato server. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Imposta un valore che indica se le istanze della classe ServicePoint usano l'algoritmo di Nagle. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Imposta il valore che indica se l'opzione 'Keep-Alive' è abilitata. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Il numero predefinito di connessioni non persistenti. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Il numero predefinito di connessioni persistenti. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Net](../)
* Libreria [Aspose.Slides](../../)