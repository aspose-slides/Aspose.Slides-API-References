---
title: Path
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona métodos para manipular rutas. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 339
url: /es/system.io/path/
---
## Clase Path

Proporciona métodos para manipular rutas. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Path
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cambia la extensión en la ruta de archivo especificada. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Determina si la ruta especificada es válida comprobando si contiene caracteres no válidos. Se lanza una excepción si la ruta contiene caracteres no válidos. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Combina los segmentos de ruta especificados en una única ruta insertando caracteres separadores de directorio entre los segmentos si es necesario. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina dos segmentos de ruta especificados en una única ruta insertando un carácter separador de directorio entre los segmentos si es necesario. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina tres segmentos de ruta especificados en una única ruta insertando caracteres separadores de directorio entre los segmentos si es necesario. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina cuatro segmentos de ruta especificados en una única ruta insertando caracteres separadores de directorio entre los segmentos si es necesario. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Devuelve el nombre del directorio referenciado por la ruta especificada. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Devuelve la extensión del archivo referenciado por la ruta especificada. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Devuelve el nombre del archivo referenciado por la ruta especificada. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Devuelve el nombre sin extensión del archivo referenciado por la ruta especificada. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Convierte la ruta especificada en una ruta absoluta. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Devuelve una matriz que contiene los caracteres que no están permitidos en los nombres de archivos. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Devuelve una matriz que contiene los caracteres que no están permitidos en los nombres de rutas. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Devuelve el directorio raíz de la ruta especificada. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Devuelve un nombre de archivo generado aleatoriamente. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Crea un nuevo archivo con un nombre único y devuelve una ruta completa a él. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Crea un nuevo archivo con un nombre único y devuelve una ruta completa a él. Es sinónimo del método [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Devuelve la ruta del directorio temporal del usuario actual. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Determina si la ruta especificada referencia un archivo con extensión. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Determina si la ruta especificada contiene una raíz. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normaliza la ruta especificada. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Devuelve una instancia de la clase boost::filesystem::path que representa la ruta especificada. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Devuelve una representación en cadena del objeto path de Boost especificado. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Un carácter alternativo usado para separar niveles de directorio en una ruta. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Un carácter usado para separar niveles de directorio en una ruta. |
| static [PathSeparator](./pathseparator/) | Un carácter separador usado para separar cadenas de rutas en variables de entorno. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Un carácter separador de volumen. |

## Observaciones

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Genera un nombre de archivo aleatorio.
  auto filename = Path::GetRandomFileName();

  // Imprime información sobre el nombre del archivo.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
Nombre de archivo: qhuzkyqv.y6p
Nombre de archivo sin extensión: qhuzkyqv
Extensión: .y6p
*/
```

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)