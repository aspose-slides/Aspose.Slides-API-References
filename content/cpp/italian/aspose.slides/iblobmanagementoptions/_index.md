---
title: IBlobManagementOptions
second_title: Riferimento API Aspose.Slides per C++
description: Un Binary Large Object (BLOB) è un dato binario memorizzato come un'unica entità, cioè il BLOB può essere un audio, un video o la presentazione stessa. Diverse tecniche vengono utilizzate per ottimizzare il consumo di memoria durante la gestione dei BLOB, che sono già stati memorizzati nella presentazione o aggiunti successivamente in modo programmatico. Utilizzando IBlobManagementOptions è possibile modificare diversi aspetti del comportamento relativi alla gestione dei BLOB per la durata dell'istanza IPresentation.
type: docs
weight: 1535
url: /it/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions classe

Un Binary Large Object (BLOB) è un dato binario memorizzato come un'unica entità, cioè il BLOB può essere un audio, un video o la presentazione stessa. Diverse tecniche vengono utilizzate per ottimizzare il consumo di memoria durante la gestione dei BLOB – che sono già stati memorizzati nella presentazione o aggiunti successivamente in modo programmatico. Utilizzando [IBlobManagementOptions](./) è possibile modificare diversi aspetti del comportamento relativi alla gestione dei BLOB per la durata dell'istanza [IPresentation](../ipresentation/).

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali pur essendo, secondo IEC 60559:1989, NaN non uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali pur essendo, secondo IEC 60559:1989, NaN non uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Questa proprietà definisce se è possibile creare file temporanei durante la gestione dei BLOB, il che riduce notevolmente il consumo di memoria ma richiede i permessi per creare file. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono utilizzati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può comportare un elevato utilizzo della memoria. Usa questa proprietà per adeguare il comportamento al tuo ambiente o ai requisiti. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Questa proprietà definisce se un'istanza della classe [Presentation](../presentation/) può essere proprietaria della sorgente – file o stream – per tutta la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante la gestione dei BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di [Presentation](../presentation/). Questo è un esempio: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | Il percorso radice dove verranno creati i file temporanei. La directory temporanea [System](../../system/) sarà usata per impostazione predefinita. Il processo di hosting deve avere i permessi per creare file e cartelle in tale percorso. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia effettivamente nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia effettivamente nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Questa proprietà definisce se è possibile creare file temporanei durante la gestione dei BLOB, il che riduce notevolmente il consumo di memoria ma richiede i permessi per creare file. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono utilizzati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può comportare un elevato utilizzo della memoria. Usa questa proprietà per adeguare il comportamento al tuo ambiente o ai requisiti. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Questa proprietà definisce se un'istanza della classe [Presentation](../presentation/) può essere proprietaria della sorgente – file o stream – per tutta la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante la gestione dei BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di [Presentation](../presentation/). Questo è un esempio: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | Il percorso radice dove verranno creati i file temporanei. La directory temporanea [System](../../system/) sarà usata per impostazione predefinita. Il processo di hosting deve avere i permessi per creare file e cartelle in tale percorso. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)