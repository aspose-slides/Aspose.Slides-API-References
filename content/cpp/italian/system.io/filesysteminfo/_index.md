---
title: FileSystemInfo
second_title: Riferimento API di Aspose.Slides per C++
description: "La classe base per FileInfo e DirectoryInfo. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 300
url: /it/system.io/filesysteminfo/
---
## classe FileSystemInfo

La classe base per [FileInfo](../fileinfo/) e [DirectoryInfo](../directoryinfo/). Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o falle di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento.

```cpp
class FileSystemInfo : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Delete](./delete/)() | Elimina l'entità rappresentata dall'oggetto corrente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual void [Finalize](./finalize/)() | Non fa nulla. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | Restituisce gli attributi dell'entità rappresentata dall'oggetto corrente. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | Restituisce la data di creazione dell'entità rappresentata dall'oggetto corrente come ora locale. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | Restituisce la data di creazione dell'entità rappresentata dall'oggetto corrente come ora UTC. |
| virtual **bool** [get_Exists](./get_exists/)() | Determina se l'entità indicata dal percorso rappresentato dall'oggetto corrente esiste. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | Restituisce l'estensione del file rappresentato dall'oggetto corrente. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | Restituisce il nome completo (incluso il percorso) dell'entità rappresentata dall'oggetto corrente. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | Restituisce l'ultima data di accesso dell'entità rappresentata dall'oggetto corrente come ora locale. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Restituisce l'ultima data di accesso dell'entità rappresentata dall'oggetto corrente come ora UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | Restituisce l'ultima data di scrittura dell'entità rappresentata dall'oggetto corrente come ora locale. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Restituisce l'ultima data di scrittura dell'entità rappresentata dall'oggetto corrente come ora UTC. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Restituisce un nome dell'entità rappresentata dall'oggetto corrente. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, realmente, ma inizializza un nuovo oggetto e consente la copia di costruttori per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, realmente, ma inizializza un nuovo oggetto e consente la copia di costruttori per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| void [Refresh](./refresh/)() | Aggiorna lo stato dell'oggetto corrente. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | Imposta gli attributi specificati sull'entità rappresentata dall'oggetto corrente. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | Imposta la data di creazione dell'entità rappresentata dall'oggetto corrente come ora locale. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | Imposta la data di creazione dell'entità rappresentata dall'oggetto corrente come ora UTC. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | Imposta l'ultima data di accesso dell'entità rappresentata dall'oggetto corrente come ora locale. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Imposta l'ultima data di accesso dell'entità rappresentata dall'oggetto corrente come ora UTC. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | Imposta l'ultima data di scrittura dell'entità rappresentata dall'oggetto corrente come ora locale. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Imposta l'ultima data di scrittura dell'entità rappresentata dall'oggetto corrente come ora UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come weak pointer (piuttosto che shared). Consente di passare i puntatori nei contenitori alla modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori smart o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori smart o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente di convertire oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori smart o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori smart o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)