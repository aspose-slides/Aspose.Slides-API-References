---
title: FileInfo
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un percorso verso un file e un file referenziato da questo percorso e fornisce metodi per manipolarlo. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 274
url: /it/system.io/fileinfo/
---
## FileInfo classe


Rappresenta un percorso verso un file e un file a cui si riferisce questo percorso e fornisce metodi per manipolarlo. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarla alle funzioni come argomento.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Metodi

| Method | Description |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Apre un file rappresentato dall'oggetto corrente per scrivere testo usando la codifica UTF-8, in modalità 'Append' senza condivisione. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Copia il file rappresentato dall'oggetto corrente nella posizione specificata. Se il file di destinazione esiste già, la copia fallisce. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Copia il file rappresentato dall'oggetto corrente nella posizione specificata. Un parametro specifica se il file di destinazione esistente deve essere sovrascritto. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Crea un file nella posizione specificata dal percorso rappresentato dall'oggetto corrente e lo apre per lettura e scrittura, in modalità troncamento e senza condivisione. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Crea un file nella posizione specificata dal percorso rappresentato dall'oggetto corrente e lo apre per scrivere testo usando la codifica UTF-8 senza condivisione. |
| void [Decrypt](./decrypt/)() | NON IMPLEMENTATO. |
| void [Delete](./delete/)() override | Rimuove il file rappresentato dall'oggetto corrente. |
| void [Encrypt](./encrypt/)() | NON IMPLEMENTATO. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Costruisce una nuova istanza della classe [FileInfo](./) che rappresenta il file specificato. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Non fa nulla. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Restituisce gli attributi dell'entità rappresentata dall'oggetto corrente. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Restituisce la data di creazione dell'entità rappresentata dall'oggetto corrente in ora locale. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Restituisce la data di creazione dell'entità rappresentata dall'oggetto corrente in ora UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Restituisce un oggetto [DirectoryInfo](../directoryinfo/) che rappresenta la directory in cui è situato il file rappresentato dall'oggetto corrente. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Restituisce il nome completo della directory in cui è situato il file rappresentato dall'oggetto corrente. |
| **bool** [get_Exists](./get_exists/)() override | Restituisce un valore che indica se il file esiste. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Restituisce l'estensione del file rappresentato dall'oggetto corrente. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Restituisce il nome completo (incluso il percorso) dell'entità rappresentata dall'oggetto corrente. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Restituisce un valore che indica se l'attributo ReadOnly è impostato. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Restituisce l'ultima ora di accesso dell'entità rappresentata dall'oggetto corrente in ora locale. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Restituisce l'ultima ora di accesso dell'entità rappresentata dall'oggetto corrente in ora UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Restituisce l'ultima ora di scrittura dell'entità rappresentata dall'oggetto corrente in ora locale. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Restituisce l'ultima ora di scrittura dell'entità rappresentata dall'oggetto corrente in ora UTC. |
| **int64_t** [get_Length](./get_length/)() | Restituisce la dimensione del file in byte. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Restituisce il nome del file. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Sposta il file rappresentato dall'oggetto corrente nella posizione specificata. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Apre il file rappresentato dall'oggetto corrente nella modalità specificata per lettura e scrittura senza condivisione. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Apre il file rappresentato dall'oggetto corrente nella modalità specificata, con il tipo di accesso specificato e senza condivisione. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Apre il file rappresentato dall'oggetto corrente nella modalità specificata, con il tipo di accesso specificato e l'opzione di condivisione. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Apre un file rappresentato dall'oggetto corrente solo per lettura, in modalità 'Open' con accesso condiviso per lettura. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Apre il file esistente nella posizione specificata dal percorso rappresentato dall'oggetto corrente per leggere testo usando la codifica UTF-8 senza condivisione. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Apre un file rappresentato dall'oggetto corrente solo per scrittura, in modalità 'OpenOrCreate' senza condivisione. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| void [Refresh](../filesysteminfo/refresh/)() | Aggiorna lo stato dell'oggetto corrente. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Sostituisce il contenuto di un file di destinazione specificato con il file rappresentato dall'oggetto [FileInfo](./) corrente e crea un backup del file sostituito. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Sostituisce il contenuto di un file di destinazione specificato con il file rappresentato dall'oggetto [FileInfo](./) corrente e crea un backup del file sostituito. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Imposta gli attributi specificati sull'entità rappresentata dall'oggetto corrente. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Imposta la data di creazione dell'entità rappresentata dall'oggetto corrente in ora locale. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Imposta la data di creazione dell'entità rappresentata dall'oggetto corrente in ora UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Imposta o rimuove l'attributo ReadOnly sul file. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Imposta l'ultima ora di accesso dell'entità rappresentata dall'oggetto corrente in ora locale. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Imposta l'ultima ora di accesso dell'entità rappresentata dall'oggetto corrente in ora UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Imposta l'ultima ora di scrittura dell'entità rappresentata dall'oggetto corrente in ora locale. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Imposta l'ultima ora di scrittura dell'entità rappresentata dall'oggetto corrente in ora UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Restituisce un percorso rappresentato dall'oggetto corrente. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [FileSystemInfo](../filesysteminfo/)
* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)