---
title: Directory
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene métodos para manipular directorios. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 235
url: /es/system.io/directory/
---
## Clase Directory

Contiene métodos para manipular directorios. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Directory
```

## Métodos

| Método | Descripción |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Crea todos los directorios en la ruta especificada si no existen. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Elimina el archivo o directorio especificado. No lanza excepciones. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos y directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determina si la ruta especificada se refiere a un directorio existente. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Devuelve la hora de creación de la entidad especificada en hora local. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Devuelve la hora de creación de la entidad especificada en hora UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Devuelve el nombre completo (incluyendo la ruta) del directorio actual. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Devuelve el directorio raíz de la ruta especificada. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos y directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Devuelve la última hora de acceso de la entidad especificada en hora local. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Devuelve la última hora de acceso de la entidad especificada en hora UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Devuelve la última hora de escritura de la entidad especificada en hora local. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Devuelve la última hora de escritura de la entidad especificada en hora UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NO IMPLEMENTADO. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Devuelve un puntero compartido al objeto [DirectoryInfo](../directoryinfo/) que representa el directorio padre de la entidad especificada. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Mueve la entidad especificada a la nueva ubicación. Si la entidad a mover es un directorio, se mueve con todo su contenido. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la hora de creación de la entidad especificada en hora local. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la hora de creación de la entidad especificada en hora UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Establece el directorio actual. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la última hora de acceso de la entidad especificada en hora local. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la última hora de acceso de la entidad especificada en hora UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la última hora de escritura de la entidad especificada en hora local. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la última hora de escritura de la entidad especificada en hora UTC. |

## Tipos definidos

| Alias | Descripción |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Un alias para un puntero compartido a un objeto IEnumerable que itera sobre un conjunto de objetos [String](../../system/string/). |

## Observaciones

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
  // Crear cadenas que contienen rutas a directorios.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Verificar si los directorios existen.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Imprimir la información del directorio temporal.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
El directorio 'C:\' existe.
El directorio 'C:\Some directory' no existe.
El directorio 'C:\Users\lanor\AppData\Local\Temp\' existe.
Hora de creación: 27.08.2021 14:21:42
Último acceso: 07.10.2021 12:16:41
Última escritura: 07.10.2021 12:16:41
*/
```

## Véase también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)