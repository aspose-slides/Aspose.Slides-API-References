---
title: BoxedEnum
second_title: Aspose.Slides per C++ Riferimento API
description: "Rappresenta un valore di enumerazione incapsulato. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 92
url: /it/system/boxedenum/
---
## BoxedEnum classe

Rappresenta un valore di enumerazione incapsulato. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../makeobject/). Non creare mai un'istanza di questo tipo nello stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../smartptr/) e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| E | Tipo del valore di enumerazione |
| UT | Il tipo sottostante dell'enumerazione **E** |

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [BoxedEnum](./boxedenum/)(E) | Costruisce un'istanza che rappresenta il valore di enumerazione specificato. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| virtual [TypeCode](../typecode/) [GetTypeCode](../boxedvaluebase/gettypecode/)() const | Restituisce il valore che rappresenta il tipo del valore incapsulato rappresentato dall'oggetto corrente. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Converte il valore della costante di enumerazione incapsulata in un valore intero a 64 bit. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanzia del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Determina se l'oggetto corrente rappresenta un valore incapsulato di tipo enum. |
| void [Lock](../object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Incapsula il valore della costante di enumerazione dell'enumerazione specificata con il nome specificato. Un parametro indica se si deve ignorare il case nell'interpretazione della stringa che specifica il nome della costante di enumerazione. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Incapsula il valore della costante di enumerazione dell'enumerazione specificata con il nome specificato. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [System::String](../string/) [ToString](./tostring/)() const override | Converte il valore incapsulato rappresentato dall'oggetto corrente in una stringa. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Converte l'oggetto incapsulato in una stringa usando la stringa di formato specificata. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa il costrutto C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [BoxedValue](../boxedvalue/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)