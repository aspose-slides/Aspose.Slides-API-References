---
title: Path
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce metodi per manipolare i percorsi. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 339
url: /it/system.io/path/
---
## classe Path


Fornisce metodi per manipolare i percorsi. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Path
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Modifica l'estensione nel percorso di file specificato. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Determina se il percorso specificato è valido controllando se contiene caratteri non validi. Viene sollevata un'eccezione se il percorso contiene caratteri non validi. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Combina i segmenti di percorso specificati in un unico percorso inserendo caratteri separatori di directory tra i segmenti, se necessario. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina i segmenti di percorso specificati in un unico percorso inserendo caratteri separatori di directory tra i segmenti, se necessario. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina i segmenti di percorso specificati in un unico percorso inserendo caratteri separatori di directory tra i segmenti, se necessario. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina i segmenti di percorso specificati in un unico percorso inserendo caratteri separatori di directory tra i segmenti, se necessario. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Restituisce il nome della directory a cui si riferisce il percorso specificato. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Restituisce l'estensione del file a cui si riferisce il percorso specificato. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Restituisce il nome del file a cui si riferisce il percorso specificato. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Restituisce il nome del file senza estensione a cui si riferisce il percorso specificato. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Converte il percorso specificato in un percorso assoluto. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Restituisce un array contenente i caratteri non ammessi nei nomi dei file. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Restituisce un array contenente i caratteri non ammessi nei nomi dei percorsi. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Restituisce la directory radice del percorso specificato. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Restituisce un nome file generato casualmente. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Crea un nuovo file con un nome univoco e restituisce un percorso completo per esso. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Crea un nuovo file con un nome univoco e restituisce un percorso completo per esso. È un sinonimo del metodo [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Restituisce il percorso della directory temporanea dell'utente corrente. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Determina se il percorso specificato fa riferimento a un file con estensione. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Determina se il percorso specificato contiene una radice. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normalizza il percorso specificato. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Restituisce un'istanza della classe boost::filesystem::path che rappresenta il percorso specificato. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Restituisce una rappresentazione stringa dell'oggetto path di Boost specificato. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Un carattere alternativo usato per separare i livelli di directory in un percorso. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Un carattere usato per separare i livelli di directory in un percorso. |
| static [PathSeparator](./pathseparator/) | Un carattere separatore usato per separare le stringhe di percorso nelle variabili d'ambiente. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Un carattere separatore di volume. |

## Osservazioni

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Genera un nome file casuale.
  auto filename = Path::GetRandomFileName();

  // Stampa informazioni sul nome del file.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## Vedi anche

* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)