---
title: StringBuilder
second_title: Riferimento API di Aspose.Slides per C++
description: "Buffer per accumulare stringhe parte per parte. Questo tipo può essere allocato sia nello stack come tipo valore sia nell'heap usando la funzione System::MakeObject(). Una volta che l'oggetto è allocato, non mescolare questi due casi d'uso: avere puntatori SmartPtr su oggetti allocati nello stack è strettamente proibito."
type: docs
weight: 326
url: /it/system.text/stringbuilder/
---
## StringBuilder classe


[Buffer](../../system/buffer/) per accumulare stringhe parte per parte. Questo tipo può essere allocato sia nello stack come tipo valore sia nell'heap usando la funzione [System::MakeObject()](../../system/makeobject/). Una volta che l'oggetto è allocato, non mescolare questi due casi d'uso: avere puntatori [SmartPtr](../../system/smartptr/) su oggetti allocati nello stack è strettamente proibito.

```cpp
class StringBuilder : public System::Object
```

## Metodi

| Method | Description |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Aggiunge un carattere al builder. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Aggiunge caratteri al builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Aggiunge una matrice di caratteri al builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Aggiunge una fetta di matrice di caratteri al builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Aggiunge una stringa al builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Aggiunge una fetta di stringa al builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Aggiunge la rappresentazione stringa dell'oggetto al builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Aggiunge il contenuto del builder al builder. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Aggiunge un valore in virgola mobile al builder. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Aggiunge un valore in virgola mobile al builder. |
| [StringBuilder](./) * [Append](./append/)(int) | Aggiunge un valore intero al builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Aggiunge un valore aritmetico al builder. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Aggiunge la rappresentazione stringa del valore enum al builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Aggiunge una stringa formattata al builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Aggiunge una stringa formattata al builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Aggiunge il carattere di nuova riga al builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Aggiunge una stringa seguita dal carattere di nuova riga al builder. |
| [StringBuilder](./) * [Clear](./clear/)() | Rimuove tutti i caratteri dal builder. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Copia i dati del builder in posizioni di array esistenti. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Assicura che la capacità di questa istanza di [System.Text.StringBuilder](./) sia almeno il valore specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| int [get_Capacity](./get_capacity/)() const | Restituisce la capacità corrente del string builder. |
| int [get_Length](./get_length/)() const | Restituisce la lunghezza della stringa attualmente nel builder. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Restituisce il carattere nella posizione specificata. |
| void [idx_set](./idx_set/)(int, char_t) | Imposta il carattere nella posizione specificata. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Inserisce una stringa nella posizione fissa del builder. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Inserisce una stringa ripetuta nella posizione fissa del builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Inserisce un carattere nella posizione fissa del builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Inserisce caratteri nella posizione fissa del builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Inserisce un valore nella posizione fissa del builder. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la copia dei sottoclasse. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la copia dei sottoclasse. |
| char_t [operator[]](./operator[]/)(int) const | Restituisce il carattere nella posizione specificata. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Rimuove un frammento dal builder. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Sostituisce la sottostringa attraverso il builder. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Sostituisce la sottostringa nell'intervallo del builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Sostituisce il carattere attraverso il builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Sostituisce il carattere nell'intervallo del builder. |
| void [set_Capacity](./set_capacity/)(int) | Imposta la capacità corrente del string builder. |
| void [set_Length](./set_length/)(int) | Accorcia o estende il string builder alla lunghezza specificata. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento n-esimo del template a un puntatore debole (anziché condiviso). Permette di cambiare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Costruttore. |
|  [StringBuilder](./stringbuilder/)(int) | Costruttore. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Costruttore. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Costruttore. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Costruttore. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Restituisce la stringa attualmente contenuta nel builder. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Restituisce la sottostringa attualmente contenuta nel builder. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
|  [~StringBuilder](./~stringbuilder/)() | Distruttore. |
## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Text](../)
* Libreria [Aspose.Slides](../../)