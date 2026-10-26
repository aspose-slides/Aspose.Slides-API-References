---
title: Directory
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene metodi per manipolare le directory. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 235
url: /it/system.io/directory/
---
## Directory classe


Contiene metodi per manipolare le directory. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Directory
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Crea tutte le directory nel percorso specificato se non esistono. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Rimuove il file o la directory specificati. Non genera eccezioni. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Cerca le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Cerca i file che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Cerca i file e le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determina se il percorso specificato fa riferimento a una directory esistente. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Restituisce l'ora di creazione dell'entità specificata come ora locale. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Restituisce l'ora di creazione dell'entità specificata come ora UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Restituisce il nome completo (incluso il percorso) della directory corrente. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Cerca le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Restituisce la directory radice del percorso specificato. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Cerca i file che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Cerca i file e le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Restituisce l'ora dell'ultimo accesso dell'entità specificata come ora locale. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Restituisce l'ora dell'ultimo accesso dell'entità specificata come ora UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Restituisce l'ora dell'ultima scrittura dell'entità specificata come ora locale. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Restituisce l'ora dell'ultima scrittura dell'entità specificata come ora UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NON IMPLEMENTATO. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Restituisce un puntatore condiviso all'oggetto [DirectoryInfo](../directoryinfo/) che rappresenta la directory padre dell'entità specificata. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Sposta l'entità specificata nella nuova posizione. Se l'entità da spostare è una directory, viene spostata con tutto il suo contenuto. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ora di creazione dell'entità specificata come ora locale. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ora di creazione dell'entità specificata come ora UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Imposta la directory corrente. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ora dell'ultimo accesso dell'entità specificata come ora locale. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ora dell'ultimo accesso dell'entità specificata come ora UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ora dell'ultima scrittura dell'entità specificata come ora locale. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Imposta l'ora dell'ultima scrittura dell'entità specificata come ora UTC. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Un alias per un puntatore condiviso a un oggetto IEnumerable che enumera un insieme di oggetti [String](../../system/string/). |

## Osservazioni



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Crea stringhe che contengono percorsi a directory.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Verifica se le directory esistono.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Stampa le informazioni della directory temporanea.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
Directory 'C:\' esiste.
Directory 'C:\Some directory' non esiste.
Directory 'C:\Users\lanor\AppData\Local\Temp\' esiste.
Ora di creazione: 27.08.2021 14:21:42
Ora dell'ultimo accesso: 07.10.2021 12:16:41
Ora dell'ultima scrittura: 07.10.2021 12:16:41
*/
```

## Vedi anche

* Namespace [System::IO](../)
* Libreria [Aspose.Slides](../../)