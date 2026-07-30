---
title: File
second_title: Riferimento API Aspose.Slides per C++
description: Fornisce metodi per manipolare i file. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 261
url: /it/system.io/file/
---
## File classe

Fornisce metodi per manipolare i file. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class File
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Aggiunge stringhe dalla collezione di stringhe specificata al file specificato usando la codifica specificata scrivendo ogni stringa in una nuova riga. Se il file specificato non esiste, viene creato. Il file viene chiuso dopo la scrittura di tutte le stringhe. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Aggiunge la stringa specificata al file specificato usando la codifica specificata. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Crea un oggetto [StreamWriter](../streamwriter/) che aggiunge testo al file specificato usando la codifica UTF-8. Se il file specificato non esiste, viene creato. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Copia il file specificato nella posizione specificata. Se il file di destinazione esiste già, un parametro indica se deve essere sovrascritto. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Crea un nuovo file (o sovrascrive quello esistente) e lo apre per accesso in lettura e scrittura usando la dimensione del buffer e le opzioni specificate. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Crea un nuovo file o apre quello esistente per scrivere testo codificato in UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NON IMPLEMENTATO. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Elimina il file o la directory specificati. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NON IMPLEMENTATO. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determina se il percorso specificato fa riferimento a un file esistente. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Restituisce gli attributi dell'entità specificata. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Restituisce la data di creazione dell'entità specificata come ora locale. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Restituisce la data di creazione dell'entità specificata come ora UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Restituisce l'ultimo accesso dell'entità specificata come ora locale. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Restituisce l'ultimo accesso dell'entità specificata come ora UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Restituisce l'ultima scrittura dell'entità specificata come ora locale. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Restituisce l'ultima scrittura dell'entità specificata come ora UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Sposta il file specificato nella nuova posizione. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Apre il file specificato nella modalità specificata per lettura e scrittura senza condivisione. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Apre il file specificato nella modalità specificata, con il tipo di accesso e l'opzione di condivisione specificati. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Apre il file specificato solo per lettura, in modalità 'Open' con accesso condiviso per lettura. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Apre il file esistente specificato per leggere testo usando la codifica UTF-8 senza condivisione. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Apre il file specificato solo per scrittura, in modalità 'OpenOrCreate' senza condivisione. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Legge il contenuto del file binario specificato in un array di byte. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Legge il contenuto del file di testo specificato riga per riga in un array di stringhe usando la codifica dei caratteri specificata. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Legge il contenuto del file di testo specificato in un unico oggetto [String](../../system/string/) usando la codifica dei caratteri specificata. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Legge il contenuto del file di testo specificato riga per riga usando la codifica dei caratteri specificata e restituisce una collezione enumerabile di stringhe, ognuna delle quali rappresenta una singola riga del contenuto del file. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Sostituisce il contenuto di un file con quello di un altro e crea un backup del file sostituito. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Imposta gli attributi specificati sul file specificato. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTATO. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTATO. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTATO. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTATO. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ultima data di scrittura dell'entità specificata come ora locale. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ultima data di scrittura dell'entità specificata come ora UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Sovrascrive il file binario specificato e scrive i byte specificati su di esso. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crea un nuovo file di testo o sovrascrive quello esistente e scrive tutte le stringhe della collezione enumerabile di stringhe specificata nel file, ogni stringa su una nuova riga, usando la codifica specificata. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crea un nuovo file di testo o sovrascrive quello esistente e scrive tutte le stringhe dell'array di stringhe specificato nel file, ogni stringa su una nuova riga, usando la codifica specificata. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crea un nuovo file di testo o sovrascrive quello esistente e scrive il contenuto della stringa specificata nel file usando la codifica specificata. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Valore predefinito del numero di byte bufferizzati durante la lettura da e la scrittura su un file. |

## Vedi anche

* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)