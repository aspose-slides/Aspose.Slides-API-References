---
title: Path
second_title: Referência da API Aspose.Slides para C++
description: Fornece métodos para manipular caminhos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.
type: docs
weight: 339
url: /pt/system.io/path/
---
## Path classe

Fornece métodos para manipular caminhos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.

```cpp
class Path
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Altera a extensão no caminho de arquivo especificado. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Determina se o caminho especificado é válido verificando se contém caracteres inválidos. Uma exceção é lançada se o caminho contiver caracteres inválidos. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Combina os segmentos de caminho especificados em um único caminho inserindo caracteres separadores de diretório entre os segmentos, se necessário. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina dois segmentos de caminho especificados em um único caminho inserindo o caractere separador de diretório entre os segmentos, se necessário. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina três segmentos de caminho especificados em um único caminho inserindo caracteres separadores de diretório entre os segmentos, se necessário. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combina quatro segmentos de caminho especificados em um único caminho inserindo caracteres separadores de diretório entre os segmentos, se necessário. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Retorna o nome do diretório referenciado pelo caminho especificado. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Retorna a extensão do arquivo referenciado pelo caminho especificado. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Retorna o nome do arquivo referenciado pelo caminho especificado. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Retorna o nome sem extensão do arquivo referenciado pelo caminho especificado. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Converte o caminho especificado em caminho absoluto. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Retorna um array contendo caracteres que não são permitidos nos nomes de arquivos. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Retorna um array contendo caracteres que não são permitidos nos nomes de caminhos. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Retorna o diretório raiz do caminho especificado. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Retorna um nome de arquivo gerado aleatoriamente. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Cria um novo arquivo com um nome único e retorna um caminho completo para ele. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Cria um novo arquivo com um nome único e retorna um caminho completo para ele. É um sinônimo do método [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Retorna o caminho do diretório temporário do usuário atual. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Determina se o caminho especificado referencia um arquivo com extensão. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Determina se o caminho especificado contém uma raiz. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normaliza o caminho especificado. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Retorna uma instância da classe boost::filesystem::path que representa o caminho especificado. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Retorna uma representação em string do objeto path da Boost especificado. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Um caractere alternativo usado para separar níveis de diretório em um caminho. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Um caractere usado para separar níveis de diretório em um caminho. |
| static [PathSeparator](./pathseparator/) | Um caractere separador usado para separar strings de caminho em variáveis de ambiente. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Um caractere separador de volume. |

## Observações

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Gere um nome de arquivo aleatório.
  auto filename = Path::GetRandomFileName();

  // Imprima informações sobre o nome do arquivo.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
Nome do arquivo: qhuzkyqv.y6p
Nome do arquivo sem extensão: qhuzkyqv
Extensão: .y6p
*/
```

## Veja Também

* Espaço de nomes [System::IO](../)
* Biblioteca [Aspose.Slides](../../)