---
title: BoxedValueBase
second_title: Riferimento API Aspose.Slides per C++
description: "Una classe base che definisce un'interfaccia e implementa alcuni metodi fondamentali di una classe discendente che rappresenta un valore incapsulato. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare tale puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 131
url: /it/system/boxedvaluebase/
---
## BoxedValueBase classe

Una classe base che definisce un'interfaccia e implementa alcuni metodi fondamentali di una classe discendente che rappresenta un valore incapsulato. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../smartptr/) e usare tale puntatore per passarla alle funzioni come argomento.

```cpp
class BoxedValueBase : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const&, T2 const&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const&, T2 const&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const&, **float** const&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const&, **double** const&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase&, void **) const | Solo per scopi interni. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| virtual [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Restituisce il valore che rappresenta il tipo del valore imballato rappresentato dall'oggetto corrente. |
| virtual **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | Converte il valore imballato rappresentato dall'oggetto corrente in un valore intero a 64 bit. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| virtual **bool** [IsBoxedEnum](./isboxedenum/)() | Determina se l'oggetto corrente rappresenta un valore imballato di tipo enum. |
| void [Lock](../object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../object/object/)([Object](../object/) const&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e abilita la copia dei sottoclasse. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e abilita la copia dei sottoclasse. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Imballa il valore della costante di enumerazione specificata con il nome specificato. Un parametro indica se il caso deve essere ignorato durante l'interpretazione della stringa che specifica il nome della costante di enumerazione. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Imballa il valore della costante di enumerazione specificata con il nome specificato. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const&, [ptr](../object/ptr/) const&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const&, T const&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const&, [String](../string/) const&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso per il valore specificato. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [System::String](../string/) [ToString](./tostring/)(const [System::String](../string/)\&) const | Converte l'oggetto imballato in stringa usando la stringa di formato specificata. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analogo del metodo C# [Object.ToString()](../object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa il costrutto C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../object/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)