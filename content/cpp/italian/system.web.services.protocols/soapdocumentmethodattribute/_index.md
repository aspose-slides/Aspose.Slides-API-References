---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides per C++ Riferimento API
description: "Specifica che tutti i messaggi SOAP passati o restituiti dal metodo utilizzano la formattazione Document. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 53
url: /it/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute classe

Specifica che tutti i messaggi SOAP passati o restituiti dal metodo utilizzano la formattazione Document. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [String](../../system/string/) [get_Action](./get_action/)() | Restituisce il valore dell'attributo 'SOAPAction'. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | Restituisce il binding per il quale un metodo di servizio web XML sta implementando un'operazione. |
| **bool** [get_OneWay](./get_oneway/)() | Restituisce un valore che indica se il client non attende che il server termini l'elaborazione del metodo. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | Restituisce un valore che indica se i parametri sono incapsulati all'interno di un unico elemento XML sotto l'elemento 'Body'. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | Restituisce il nome dell'elemento XML associato alla richiesta SOAP, definito in una descrizione di servizio come un'operazione. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | Restituisce lo spazio dei nomi associato alla richiesta SOAP. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | Restituisce il nome dell'elemento XML associato alla risposta SOAP. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | Restituisce lo spazio dei nomi associato alla risposta SOAP. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | Restituisce un valore che determina il metodo di codifica del messaggio. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimenti associata all'oggetto. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Restituisce un attributo personalizzato di un tipo specificato applicato al tipo specificato. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Restituisce tutti gli attributi personalizzati applicati al tipo specificato. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il locking dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_Action](./set_action/)([String](../../system/string/)) | Imposta il valore dell'attributo 'SOAPAction'. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | Imposta il binding per il quale un metodo di servizio web XML sta implementando un'operazione. |
| void [set_OneWay](./set_oneway/)(**bool**) | Imposta un valore che indica se il client non attende che il server termini l'elaborazione del metodo. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | Imposta un valore che indica se i parametri sono incapsulati all'interno di un unico elemento XML sotto l'elemento 'Body'. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | Imposta il nome dell'elemento XML associato alla richiesta SOAP, definito in una descrizione di servizio come un'operazione. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | Imposta lo spazio dei nomi associato alla richiesta SOAP. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | Imposta il nome dell'elemento XML associato alla risposta SOAP. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | Imposta lo spazio dei nomi associato alla risposta SOAP. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Imposta un valore che determina il metodo di codifica del messaggio. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Costruisce una nuova istanza. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | Costruisce una nuova istanza. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Attribute](../../system/attribute/)
* Spazio dei nomi [System::Web::Services::Protocols](../)
* Library [Aspose.Slides](../../)