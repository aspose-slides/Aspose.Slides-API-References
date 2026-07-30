---
title: SimpleEnumerator
second_title: Riferimento API Aspose.Slides per C++
description: "Classe iterator per contenitori semplici che contengono elementi direttamente usando le funzioni rbegin() e rend() . Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject() . Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 508
url: /it/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator classe

Iterator classe per contenitori semplici che contengono direttamente elementi usando le funzioni rbegin() e rend(). Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Container | Tipo di contenitore da iterare. |
| Element | Tipo di elemento. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [IEnumerator](../ienumerator/) * [AsVirtualizedIterator](../ienumerator/asvirtualizediterator/)() | Prepara l'iteratore per essere utilizzato dalla classe VirtualizedIterator. |
| [BaseEnumerator](../baseenumerator/baseenumerator/)(const [Object::ptr](../../system/object/ptr/)\&, Container\&) | Inizializza l'iteratore. |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Clona l'iteratore corrente. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../ienumerator/current/)() const | Ottiene l'elemento corrente. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Non fa nulla. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Element\> [get_Current](./get_current/)() const override | Ottiene l'elemento 'corrente'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [IEnumerator](../ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../ienumerator/incrementiterator/)() override | Sposta l'iteratore di un passo in avanti. |
| void [InitializeIterator](../ienumerator/initializeiterator/)() override | Esegue la prima chiamata [MoveNext()](../ienumerator/movenext/) e prepara l'oggetto enumeratore per essere usato da VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **bool** [IsValid](../baseenumerator/isvalid/)() const | Controlla se [MoveNext()](../baseenumerator/movenext/) è stato chiamato e la fine non è stata raggiunta. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| void [MarkOwnedByVirtualizedIterator](../ienumerator/markownedbyvirtualizediterator/)() | Segna l'enumeratore posseduto dall'iteratore virtualizzato. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita il cloning di tipi personalizzati. |
| **bool** [MoveNext](../baseenumerator/movenext/)() override | Incremento in stile enumeratore. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [Reset](../baseenumerator/reset/)() override | Reimposta l'enumeratore per consentire la rielettura degli elementi. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del modello a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [SimpleEnumerator](./simpleenumerator/)([Object::ptr](../../system/object/ptr/), Container\&) | Crea un iteratore semplice. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [~IEnumerator](../ienumerator/~ienumerator/)() |  |
| virtual [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [BaseEnumerator](../baseenumerator/)
* Namespace [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)